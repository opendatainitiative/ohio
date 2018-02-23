---
layout: default
permalink: /index-details
title: Index Details
---

## {{ page.title }} Open Source Policy and Legislation

<table cellpadding="10">
	<tr>
		<th>Name</th><th>State</th><th>Bill Number</th><th>Introduced</th><th>Last Action</th><th>Action Date</th><th>Bill Url</th>
	</tr>
{% for Name in site.data.opensource-legislation %}
  <tr>
  	<td width="10%" align="center">{{ Name.Name }}</td>
  	<td width="05%" align="center">{{ Name.State }}</td>
  	<td width="05%" align="center">{{ Name.Bill-Number }}</td>
  	<td width="25%" align="center">{{ Name.Introduced }}</td>
  	<td width="25%" align="center">{{ Name.Last-Action }}</td>
  	<td width="05%" align="center">{{ Name.Action-Date }}</td>
  	<td width="25%" align="center"><a href="{{ Name.Bill-Url }}">{{ Name.Bill-Url }}</a></td>
  </tr>
{% endfor %}
</table>
