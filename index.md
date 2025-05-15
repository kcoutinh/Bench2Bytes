---
layout: home
title: "Bench2Bytes" 
---

Welcome! This is my journey as a wet lab biologist learning the dark side of computational biology.

{% assign latest_post = site.posts | first %}

## Latest Post

### [{{ latest_post.title }}]({{ latest_post.url | relative_url }})

*{{ latest_post.date | date: "%B %d, %Y" }}*

{{ latest_post.excerpt }}

[Read more]({{ latest_post.url | relative_url }})
