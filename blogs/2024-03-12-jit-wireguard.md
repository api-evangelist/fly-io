---
title: "JIT WireGuard"
url: "https://fly.io/blog/jit-wireguard-peers/"
date: "2024-03-12"
feed_url: "https://fly.io/blog/feed.xml"
---
We’re Fly.io and we transmute containers into VMs, running them on our hardware around the world with the power of Firecracker alchemy. We do a lot of stuff with WireGuard, which has become a part of our customer API. This is a quick story about some tricks we played to make WireGuard faster and more scalable for the hundreds of thousands of people who now use it here.
