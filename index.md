---
layout: default
permalink: /
title: Home
---

## Existing Open Source Policy and Legislation

<table cellpadding="10">
	<tr>
		<th>Name</th><th>State</th><th>Bill Number</th><th>Introduced</th><th>Last Action</th><th>Action Date</th><th>Bill Url</th>
	</tr>
{% for Name in site.data.opensource-legislation %}
  <tr>
  	<td>{{ Name.Name }}</td>
  	<td>{{ Name.State }}</td>
  	<td>{{ Name.Bill-Number }}</td>
  	<td>{{ Name.Introduced }}</td>
  	<td>{{ Name.Last-Action }}</td>
  	<td>{{ Name.Action-Date }}</td>
  	<td><a href="{{ Name.Bill-Url }}">{{ Name.Bill-Url }}</a></td>
  </tr>
{% endfor %}
</table>

<!--
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
    -->