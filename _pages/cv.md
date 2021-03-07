---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>

	.table_container {
		width: 100%;
	}

	table.cv {
		padding: 15px;
		text-align: left;
		width: 80%;
		max-width: 700px;
		border: none;
	}

	table.cv tr {
		display: block;
		margin-top: 30px;
		margin-bottom: 30px;
		vertical-align: top;
	}

	table.cv td.year {
		width: 100px;
		vertical-align: top;
	}

	table.cv td.content .title {
		margin-bottom: 10px;
		font-weight: bold;
	}

	table.cv td.content .affiliation {
		margin-bottom: 5px;
	}

	table.cv td.content .description {
		position: relative;
	}

	table.cv td.content .description .thesis {
		display: flex;
		flex-direction: row;
	}

	table.cv td.content .description .thesis .thesis_title {
		flex-grow: 1;
	}

	table.cv td.content .description .thesis .label {
		margin-right: 10px;
		flex-grow: 1;
	}
</style>

Education
======

<div class="table_container">
	<table class="cv">
		<tr>
			<td class="year">2021</td>
			<td class="content">
				<div  class="title">M.Sc. in Physics</div>
				<div class="description">
					<div class="affiliation"> Humboldt-Universität zu Berlin </div>
					<div class="thesis">
						<div class="label">Thesis:</div>
						<div class="thesis_title">
							"An Analytic Approach to the Mean-First-Passage-Time Phase of Isotropic Stochastic Oscillators"
						</div>
					</div>
				</div>
			</td>
		</tr>
		<tr>
			<td class="year">2019</td>
			<td class="content">
				<div class="title"> B.Sc. in Physics</div>
   				<div class="description">
    					<div class="affiliation"> Humboldt-Universität zu Berlin </div>
    					<div class="thesis"> 
						<div class="label">Thesis:</div> 
						<div class="thesis_title">
							"Spatial modeling of cell polarization in <I>Saccharomyces cerevisiae</I>: Understanding the interplay of GTPase cycling and the cell's transport system"
     						</div>
    					</div>
   				</div>
			</td>
		</tr>
	</table>
</div>

Research and Work Experience
======

<div class="table_container">
	<table class="cv">
		<tr>
			<td class="year">2015--2018</td>
			<td class="content">
				<div class="title">Student Assistant</div>
				<div class="description">
					<div class="affiliation"><a href="https://rumo.biologie.hu-berlin.de/tbp/index.php/en/">Theoretical Biophysics</a> group of Prof. Dr. Dr. h.c. Edda Klipp</div>
				</div>
			</td>
		</tr>
	</table>
</div>


<!--  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
-->
