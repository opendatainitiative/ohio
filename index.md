---
layout: default
permalink: /
title: Home
---

## Summary Ohio Open Data Sources

<table cellpadding="10" border="1">
	<tr>
		<th>Organization</th><th>Source-Url</th><th>Description</th>
	</tr>
{% for Org in site.data.opendata-sources %}
  <tr>
  	<td class="tablecolumn largetablecolumn" align="center">{{ Org.Organization }}</td>
  	<td class="tablecolumn" align="center"><a href="{{ Org.Source-Url }}">{{ Org.Source-Url }}</a></td>
  	<td class="tablecolumn largetablecolumn" align="center">{{ Org.Description }}</td>
  </tr>
{% endfor %}
</table>
