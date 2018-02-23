---
layout: default
permalink: /
title: Home
---

## Summary Open Source Policy and Legislation

<table cellpadding="10">
	<tr>
		<th>Name</th><th>State</th><th>Action Date</th><th>Bill Url</th>
	</tr>
{% for Name in site.data.opensource-legislation %}
  <tr>
  	<td width="25%" align="center">{{ Name.Name }}</td>
  	<td width="25%" align="center">{{ Name.State }}</td>
  	<td width="25%" align="center">{{ Name.Action-Date }}</td>
  	<td width="25%" align="center"><a href="{{ Name.Bill-Url }}">{{ Name.Bill-Url }}</a></td>
  </tr>
{% endfor %}
</table>
