---
layout: default
permalink: /
title: Home
---
# DataOhio Landing Page
## Overview
From our first meeting, we have identified these five tasks from our last meeting as next steps for us to meet and work on:
<ol>
<li>Start cataloging where data lives in Ohio</li>
<li>Reduce the cost of municipal bonds with better reporting standards</li>
<li>Getting newspapers onboard by reducing their data gathering overhead (current Ohio news topics for Data) </li>
<li>Creating the DataOhio board through legislation (finding the next champion) and start defining what DataOhio operations should be (what are the current reporting requirements, how can it be streamlined, creating or adopting accounting standards)</li>
<li>Break the policy and advocates into two separate groups, so groups like the state librarian can be involved.</li>
</ol>

## Meetings
<ul>
<li><a href="https://docs.google.com/document/d/10ege32EMGPdF6TH-B2NGlSXiNO3WPkm_9z7pQcXUKRw/edit?usp=sharing">Meeting minutes</a>
</li>
<li><a href="https://www.eventbrite.com/e/september-2018-dataohio-meeting-tickets-46860402726">17 September 2018  Ohio State Library, 10:00am -12:00pm EST</a>
</li>
<li><a href="https://www.eventbrite.com/e/august-2018-dataohio-meeting-tickets-46860373639">16 August 2018  Ohio State Library, 10:00am -12:00pm EST</a>
</li>
<li><a href="https://www.eventbrite.com/e/july-2018-dataohio-meeting-tickets-46860146961">18 July 2018  Ohio State Library, 10:00am -12:00pm EST</a>
</li>
<li><a href="https://www.eventbrite.com/e/july-2018-dataohio-meeting-tickets-46860146961">20 June 2018  Ohio State Library, 10:00am -12:00pm EST</a>
</li>
<li><a href="https://www.eventbrite.com/e/ohio-dataohio-board-meeting-tickets-44963746777#">23 May 2018, Ohio State Library, 1:30-3:30pm EST</a>
</li>
</ul>

## Discussion
Find all our conversations online and available to be read. Don't be shy, join the mailing list and lets work together.<br />

{% raw %}
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="560" height="420" src="https://lists.opendatainitiative.io/pipermail/opendatainitiative/"></iframe>
{% endraw %}
		
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
