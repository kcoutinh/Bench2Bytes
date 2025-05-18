---
layout: default
title: "Bench2Bytes"
---
<img src="assets/images/bench2bytes-banner.png"
     alt="Bench 2 Bytes banner"
     style="display: block; max-width: 100%; height: auto; margin: 0 auto; border-radius: 12px; box-shadow: 2px 2px 12px rgba(0,0,0,0.1);" />

Hi, I’m Kristen Coutinho — a PhD student exploring gene regulation using both **wet lab experiments** and **computational biology**.

Bench2Bytes is where I will be sharing ideas, experiences, and lessons learned while working with:
- RNA-seq, ATAC-seq, and single-cell datasets  
- Tools like DESeq2, edgeR, Seurat, and Scanpy  
- Workflow design, quality control, and efficiency tips  

Each post reflects real decisions I made during research — how I think through a tool, what I watch for, and the tradeoffs that matter when working with complex data. 

Whether you're just starting out or refining your own approach to bioinformatics, I hope you’ll find something useful here.

> From bench to bytes — one thoughtful analysis at a time.

<img src="assets/images/pipeline.png" alt="Bioinformatics sketch" style="width:100%; margin-top: 24px; border-radius: 12px;" />


<hr />

{% assign latest_post = site.posts | first %}

<h2>Latest Post</h2>

<h3><a href="{{ latest_post.url | relative_url }}">{{ latest_post.title }}</a></h3>

<p><em>{{ latest_post.date | date: "%B %d, %Y" }}</em></p>

<p>{{ latest_post.excerpt }}</p>

<p><a href="{{ latest_post.url | relative_url }}">Read more</a></p>

