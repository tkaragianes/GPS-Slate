# GPS-Slate
An offline-capable site to produce a "slate" page for a mobile device to show GPS coordinates.
---
This repo is a super simple "web app" built for a data-gathering trip. We needed a way to quickly identify where a range of pictures were being taken. My solution is a GPS-capable "slate" (the board used in filming to identify the scene being shot). Before and after each set of pictures, open the slate web app, get your GPS coordinates, and take a picture of the slate.

The app includes a Service Worker to enable offline operation. This is particularly important since we will be out in the woods where network access will be spotty at best. Obviously, this app is meant to be used with a GPS-equipped mobile device.
