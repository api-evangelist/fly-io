---
title: "Corrosion"
url: "https://fly.io/blog/corrosion/"
date: "2025-10-22"
author: ""
feed_url: "https://fly.io/blog/feed.xml"
---
Fly.io transmogrifies Docker containers into Fly Machines: micro-VMs running on our own hardware all over the world. The hardest part of running this platform isn’t managing the servers, and it isn’t operating the network; it’s gluing those two things together. Several times a second, as customer CI/CD pipelines tear up or bring down Fly Machines , our state synchronization system blasts updates across our internal mesh, so that edge proxies from Tokyo to Amsterdam can keep the accurate routing table that allows them to route requests for applications to the nearest customer instances.
