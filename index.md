---
layout: default
permalink: /
title: Home
---
# Create an index of public policies that support open source

## Background
* Putting the people and resources together
* Establish a network of policy domain experts and enthusiasts
* Maintain an inventory of free and open source state and federal public policy and resources that can be used by anyone. Exclude universities for right now.
  * Open source software technologies
  * Procurement policies
  * Adoption/acquisition
  * Contribution/contributor
  * IP issues that are unique to government
* Update [current working group detail](https://wiki.opensource.org/bin/Main/Open+Source+Initiative+Working+Groups/PublicPolicyIP/)
* Update [current working group](https://opensource.org/working_groups#public)

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