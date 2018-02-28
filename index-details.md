---
layout: default
permalink: /index-details
title: Index Details
---

## {{ page.title }} Open Source Policy and Legislation

<table cellpadding="10" border="1">
	<tr>
		<th>Name</th><th>State</th><th>Bill Number</th><th>Introduced</th><th>Last Action</th><th>Action Date</th><th>Bill Url</th>
	</tr>
{% for Name in site.data.opensource-legislation %}
  <tr>
  	<td class="tablecolumn largetablecolumn" align="center">{{ Name.Name }}</td>
  	<td class="tablecolumn" align="center">{{ Name.State }}</td>
  	<td class="tablecolumn" align="center">{{ Name.Bill-Number }}</td>
  	<td class="tablecolumn largetablecolumn" align="center">{{ Name.Introduced }}</td>
  	<td class="tablecolumn largetablecolumn" align="center">{{ Name.Last-Action }}</td>
  	<td class="tablecolumn largetablecolumn" align="center">{{ Name.Action-Date }}</td>
  	<td class="tablecolumn largetablecolumn" align="center"><a href="{{ Name.Bill-Url }}">{{ Name.Bill-Url }}</a></td>
  </tr>
{% endfor %}
</table>
