---
title: "Taming A Voracious Rust Proxy"
url: "https://fly.io/blog/taming-rust-proxy/"
date: "2025-02-26"
feed_url: "https://fly.io/blog/feed.xml"
---
Here’s a fun bug. The basic idea of our service is that we run containers for our users, as hardware-isolated virtual machines (Fly Machines), on hardware we own around the world. What makes that interesting is that we also connect every Fly Machine to a global Anycast network.
