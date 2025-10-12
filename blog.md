---
layout: page
title: "Blog"
permalink: /blog/
---

<h2>Latest Posts</h2>

{%- if site.posts == empty -%}
<p>No posts yet — check back soon!</p>
{%- endif -%}


<ul class="post-list">
  {%- for post in site.posts -%}
  <li>
    <a href="{{ post.url | relative_url }}" class="post-link">
      <strong>{{ post.title }}</strong>
    </a>
    <br />
    <small class="post-date">{{ post.date | date: "%b %d, %Y" }}</small>
    <p class="post-excerpt">
      {{ post.excerpt | strip_html | truncate: 160 }}
    </p>
  </li>
  {%- endfor -%}
</ul>
