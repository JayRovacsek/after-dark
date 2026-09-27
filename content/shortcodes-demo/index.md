+++
title = "Shortcodes Demos"
date = 2017-09-24

[taxonomies]
categories = ["demo"]
tags = ["gif", "fancy"]
+++

"after-dark" comes with some handy shortcodes to make your life easier and
your posts more exciting.

<!-- more -->

Here are some examples:

# GIF-Suport

Level up your posts with GIFs!

{{ <gif sources={["assets/video.mp4"]} width={50} base_url={config.base_url} page_path={page.path} /> }}

# Fancy Notes

{% <note> %}
**Note:** Some really insightful note here.

$$ \sum\_{i=1}^{n} i = \frac{n(n+1)}{2} $$
{% </note> %}

# YouTube Video Embedding

{{ <youtube id="ym3y13nA3ew" width={80} /> }}

# Audio File Embedding

{{ <audio source="assets/audio.mp3" base_url={config.base_url} page_path={page.path} /> }}

> If you're still falling for this, I don't know what to tell you.
