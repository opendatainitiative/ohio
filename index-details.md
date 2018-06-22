---
layout: default
permalink: /index-details
title: Index Details
---

## {{ page.title }} Ohio Open Data Sources

<table cellpadding="10" border="1">
	<tr>
		<th>Organization</th><th>Source-Url</th><th>Description</th><th>Notes</th>
	</tr>
{% for Org in site.data.opendata-sources %}
  <tr>
  	<td class="tablecolumn largetablecolumn" align="center">{{ Org.Organization }}</td>
  	<td class="tablecolumn" align="center"><a href="{{ Org.Source-Url }}">{{ Org.Source-Url }}</a></td>
  	<td class="tablecolumn" align="center">{{ Org.Description }}</td>
  	<td class="tablecolumn largetablecolumn" align="center">{{ Org.Notes }}</td>
  </tr>
{% endfor %}
</table>
