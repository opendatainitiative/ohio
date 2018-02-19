---
layout: default
permalink: /
title: Home
---
# Create an index of public policies that support open source

## Background

  * [Current working group](https://wiki.opensource.org/bin/Main/Open+Source+Initiative+Working+Groups/PublicPolicyIP/)

## Existing Open Source Policy and Legislation with analysis
<table cellpadding="10">
    {% for post in site.categories.legislation %}
      <tr>
            <td>{{ post.date | date: '%B %d, %Y' }}</td>
            <td>{{ post.title }}</td>
      <tr>
            <td colspan="2"><a href="{{ site.baseurl }}{{ post.url }}">go to details</a></td>
      </tr>
      <tr>
            <td colspan="2"><hr></td>
      </tr>
    {% endfor %}