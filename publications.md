---
layout: page
title: Publications
permalink: /publications/
---
<div class="row">
  <div class="col-sm-12 col-xs-12"><img class="img-responsive" src="{{ "/img/pubb.png" }}" style="max-height: 200px"></div>
</div>

*Last update 2nd February 2020*

<div class="container" style="width: 100%; padding-left: 0px; padding-right: 0px;">
	<div class="row">
		<div class="col-12 hidden-xs hidden-sm" role="complementary">
			<div id="sidebar" class="papers-sidebar" role="complementary">
				<h2>Search</h2>
				<input type="text" class="text-input" id="filter" value="" type="search"/>
				<h2>Go to</h2>
				<ul class="nav nav-stacked">
					<li><a href="#type_article">Journal articles</a></li>
					<li><a href="#type_proceedings">Conference proceedings</a></li>
					<li><a href="#type_incollection">Conference articles (in book)</a></li>
					<li><a href="#type_inproceedings">Conference articles</a></li>
					<li><a href="#type_techreport">Technical reports</a></li>
					<li><a href="#type_misc">Others</a></li>
				</ul>
			</div>
		</div>
		<div class="col-12" role="main">
        {% imbiber francesca.bib groupby:classthenyear idswithprefix:type_ %}
		</div>
	</div>
</div>
