Fedora Sharding Benchmark Test(s)
=================================

MediaShelf has modified ActiveFedora to support sharding of Fedora Repositories.  This means that you can transparently run Hydra heads on a system sharded across any number of Fedora Repositories.  Docs on how Fedora Sharding works and how to use it are in (Fedora Sharding Documentation)[https://docs.google.com/document/d/1n-oNcEx41FOF8atKpoimascr36V9unHzB4geYCWTaQM/edit?pli=1] document.

These Benchmark tests are meant to assess when it is beneficial/necessary to shard your Fedora Repository and how much benefit there is to sharding.

Test: Max Requests
==================
Goal: Assess the maximum number of write requests Fedora can handle, assess effect of sharding on this limit.

For the test harness, we’re aiming for the simplest harness that causes a single Fedora to fall down on write requests