---
layout: page-with-side-nav
title: Documentatie ImZTC
folder_files:
  - title: Diagram ZTC incl attribuutsoorten (jpg)
    path: documenten/Diagram_ZTC_incl_attribuutsoorten.jpg
    group: 21
    versie: 2.1
    status: Definitief
    omschrijving: Diagram Informatiemodel ZTC versie 2.1
    datum: 01-07-2014
  - title: GEMMA ZTC2 - Informatiemodel v2.1 20140701 (pdf)
    path: documenten/GEMMA_ZTC2_-_Informatiemodel_v2.1_20140701.pdf
    group: 21
    versie: 2.1
    status: Definitief
    omschrijving: Informatiemodel ZTC versie 2.1
    datum: 01-07-2014
  - title: GEMMA ZTC2 - Informatiemodel v2.1 20140701 met gemarkeerde wijzigingen (pdf)
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
  - title: ImZTC 02.1 in gebruik UML (EAP) (zip)
    path: documenten/ImZTC_02.1_in_gebruik.zip
    group: 21
    versie: 2.1
    status: Definitief
    omschrijving: Informatiemodel ZTC versie 2.1 _ UML (EAP)
    datum: 01-07-2014
  - title: GEMMA Referentiezaaktypecatalogus (zip)
    path: documenten/GEMMA_Referentiezaaktypecatalogus_20141231.zip
    group: 1
    versie: 
    status: In bewerking
    omschrijving: 
    datum: 20141231
  - title: GEMMA ZTC 2 - Begeleidend Document (pdf)
    path: documenten/GEMMA_ZTC2_-_Begeleidend_document_v2.1.pdf
    group: 1
    versie: 2.1
    status: Definitief
    omschrijving: 
    datum: 20140701
  - title: GEMMA ZTC2 - Zaaktypesjabloon en Toelichting v2.1 (zip)
    path: documenten/GEMMA_ZTC2_-_Zaaktypesjabloon_en_Toelichting_v2.1_2.zip
    group: 1
    versie: 2.1
    status: Definitief
    omschrijving: 
    datum: 20160707
  - title: Voorbeeldzaaktypencatalogus OD haaglanden (pdf)
    path: documenten/OD_Haaglanden_-_Zaaktypecatalogus_v1.0_-_20120210.pdf
    group: 1
    versie: 1.0
    status: In bewerking
    omschrijving: 
    datum: 20120210
  - title: Voorbeeldzaaktypecatalogus ZTC2 (zip)
    path: documenten/ZTC2_-_Voorbeeldzaaktypen.zip
    group: 1
    versie: 1.0
    status: Definitief
    omschrijving: 
    datum: 20150109
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
			{% if i.group == 21 %} 
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

## Zaaktypecatalogus

De GEMMA Zaaktypecatalogus bestaat uit de volgende onderdelen:

* het Begeleidend document met de visie van VNG Realisatie op de zaaktypecatalogus en de uitgangspunten, het gebruik, de opzet, het informatiemodel van de GEMMA Zaaktypecatalogus 2 (ImZTC 2.1) en een beschrijving van de wijze waarop de GEMMA ZTC2 wordt beheerd (het Beheermodel).
* de Referentie-zaaktype-beschrijvingen (‘Bezwaar behandelen’, ‘Subsidieaanvraag behandelen’, etc.), die kunnen dienen als startpunt voor de uitwerking van eigen, daarvan afgeleide, zaaktypen,
* een Sjabloon voor het specificeren van een zaaktype, ook te gebruiken voor ‘het goede gesprek’ over de vertaling van een proces naar een zaaktype en voor het registreren van het zaaktype in een applicatie,
* zaaktypecatalogi met standaard- en voorbeeldzaaktypen.

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th><th>Versiedatum</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 1 %} 
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
