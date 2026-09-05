---
layout: gallery
# Required: used unconditionally as the page <h1> and index-card <h2>; empty or missing renders a blank heading.
title: Ski Trip
# Required: must be a number, present on every document in this collection. Missing sorts this item to the end with no error; a non-numeric value renders a visible "Liquid error" string on the index/nav instead of failing to build.
weight: 3
location: Chamonix
# Optional: "landscape" (default), "portrait", or "mixed" - controls the slideshow frame's aspect ratio. See _layouts/gallery.html.
orientation: portrait
time-period:
  start: 1/10/2022
  end: 1/17/2022
# Required for the galleries index thumbnail (gallery-item.html reads images[0] unguarded). Optional for this page itself, which skips the slideshow gracefully if absent.
images: [img1.jpg, img2.jpg, img3.jpg]
---

A week on the slopes with old friends.
