---
layout: default
title: "Hello World"
date: 2026-04-28
navbar_title: Blogs
---

<div class="row mt-3">
    <div class="col">
        <div class="card border-0 shadow-sm bg-white">
            <div class="card-body p-4">
                <h2>{{ page.title }}</h2>
                <p class="text-muted small">{{ page.date | date: "%B %d, %Y" }}</p>
                <hr>
                <p>This is my first blog post. Welcome to my blog!</p>
            </div>
        </div>
    </div>
</div>
