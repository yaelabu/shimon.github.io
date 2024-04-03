---
title: "Shimon Marom Lab - research"
layout: gridlay
excerpt: "Shimon Marom Lab -- research."
sitemap: false
permalink: /research/
---


# Publications  

*For a full list go to [ORCID](https://orcid.org/0000-0002-9138-4833). For Selected publication on [Ion channels & excitability](###ion-channels-&-excitability), [Psychology](###psychology), or see bellow.

## Representative Publications


{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>

## Selected publications

### Ion channels & excitability



#### multiple states and scaling of rates

{% for publi in site.data.publist %}

{% if publi.multiple == 1 %}


  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}

####  critical fluctuations

{% for publi in site.data.publist %}

{% if publi.critical == 1 %}


  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}



####  Parametrization

{% for publi in site.data.publist %}

{% if publi.Parametrization == 1 %}


  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}

####  Axonal Resilience

{% for publi in site.data.publist %}

{% if publi.axonal == 1 %}


  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}

####  Resilience of neuronal excitability across time scales


{% for publi in site.data.publist %}

{% if publi.resilience == 1 %}


  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}


### Neural networks

#### Learning

{% for publi in site.data.publist %}

{% if publi.learning == 1 %}


  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}

#### Adaptation

{% for publi in site.data.publist %}

{% if publi.adaptation == 1 %}


  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}

#### Representation

{% for publi in site.data.publist %}

{% if publi.representation == 1 %}


  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}


#### Dynamics

{% for publi in site.data.publist %}

{% if publi.dynamics == 1 %}


  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}



#### Neuromodulation

{% for publi in site.data.publist %}

{% if publi.neuromodulation == 1 %}


  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}




#### Precarious reverse engineering

{% for publi in site.data.publist %}

{% if publi.precarious == 1 %}


  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}



#### Time scales

{% for publi in site.data.publist %}

{% if publi.timescales == 1 %}


  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}

## Psychology

### Book

{% for publi in site.data.publist %}

{% if publi.psychology_book == 1 %}


  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}


### Perception

{% for publi in site.data.publist %}

{% if publi.perception == 1 %}


  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}

### Viewpoint

{% for publi in site.data.publist %}

{% if publi.psychology_viewpoint == 1 %}


  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}

## General readership


{% for publi in site.data.publist %}

{% if publi.general == 1 %}


  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}


