---
title: "Cooperative Perception for Self-Driving Cars"
excerpt: "Recently, I've been working on Cooperative Perception for a 2-vehicle system"
collection: projects
header:
    teaser: /assets/images/projects/coop-sensing/coop-sensing.gif
---

Since late 2018 I've been working on cooperative perception for a pair of self-driving cars.  The general idea is that one of the cars follows the other, with the follower having only low-cost sensors like cameras and radar.  The problem is then to fuse perception information from both vehicles, dealing with network latency and measurement uncertainty while doing data association and filtering.

Here's a video of the system running in simulation:

![Our cooperative sensing system running in simulation](/assets/images/projects/coop-sensing/coop-sensing.gif)

We had some physical vehicles that we tested on as well, but I don't have video from those.
