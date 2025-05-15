---
layout: default
title: "Bench2Bytes"
---

<h1>Bench2Bytes</h1>

<p>Welcome! This is my journey as a wet lab biologist learning the dark side of computational biology.</p>

<hr />

{% assign latest_post = site.posts | first %}

<h2>Latest Post</h2>

<h3><a href="{{ latest_post.url | relative_url }}">{{ latest_post.title }}</a></h3>

<p><em>{{ latest_post.date | date: "%B %d, %Y" }}</em></p>

<p>{{ latest_post.excerpt }}</p>

<p><a href="{{ latest_post.url | relative_url }}">Read more</a></p>

