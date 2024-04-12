---
layout: page-with-side-nav
title: Documentatie ImZTC
folder_files:
  - title:  Diagram ZTC incl attribuutsoorten (jpg)
    path: documenten/Diagram_ZTC_incl_attribuutsoorten.jpg
    group: 21
    versie: 2.1
    status: Definitief
    omschrijving: Diagram Informatiemodel ZTC versie 2.1
    datum: 01-07-2014
  - title:  GEMMA ZTC2 - Informatiemodel v2.1 20140701 (pdf)
    path: documenten/GEMMA_ZTC2_-_Informatiemodel_v2.1_20140701.pdf
    group: 21
    versie: 2.1
    status: Definitief
    omschrijving: Informatiemodel ZTC versie 2.1
    datum: 01-07-2014
  - title:  GEMMA ZTC2 - Informatiemodel v2.1 20140701 met gemarkeerde wijzigingen (pdf)
    path: documenten/GEMMA_ZTC2_-_Informatiemodel_v2.1_20140701_met_gemarkeerde_wijzigingen.pdf
    group: 21
    versie: 2.1
    status: Definitief
    omschrijving: Informatiemodel ZTC versie 2.1 met gemarkeerde wijzigingen t.o.v. versie 2.0
    datum: 01-07-2014
  - title: GEMMA ZTC2 - referentiewaardenlijsten v2.1 (zip)
    path: documenten/GEMMA_ZTC2_-_referentiewaardenlijsten_v2.1.xlsx.zip
    group: 21
    versie: 2.1
    status: Definitief
    omschrijving: 
    datum: 01-07-2014
  - title:  ImZTC 02.1 in gebruik UML (EAP) (zip)
    path: documenten/ImZTC_02.1_in_gebruik.zip
    group: 21
    versie: 2.1
    status: Definitief
    omschrijving: Informatiemodel ZTC versie 2.1 _ UML (EAP)
    datum: 01-07-2014
---

# Documentatie

## ImZTC 2.1

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th><th>Versiedatum</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 10 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
					<td>{{ i.datum }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>
