---
title: "Shimon Marom - Links"
layout: textlay
excerpt: "Shimon Marom -- Links"
sitemap: false
permalink: /Links/
---
# Links to Open Data, Codes and Teachings

- Open [datasets and codes](https://data.mendeley.com/research-data/?type=DATASET&search=Shimon%20Marom)
- Long [recording sessions](https://data.mendeley.com/datasets/4ztc7yxngf/1) from ex-vivo networks of cortical neurons using a multi-electrode-array.
- Long (hours) time series of [single neuron responses](https://data.mendeley.com/datasets/ybn82tr8rk/1) (1/0) to 20-25 Hz stimulation (Gal et al, 2009)
- Biological Implementation (cortical neurons in-vitro) of a [Braitenberg Vehicle](https://data.mendeley.com/datasets/bcrvd4mdsf/1) (Marom et al, 2009)
- Mathematica® lecture notes (CDF, computational document format) on [membrane excitability](https://data.mendeley.com/datasets/2kn5ymgwvg/1)
- Mathematica® Notebook for reconstructing a 2D [S-K phase diagram](https://data.mendeley.com/datasets/sc3t4jvv78/1) of membrane excitability (Ori et al, 2008)
- Recorded lecture on "Neurophysiology and depth-psychology: a possible [impossible dialogue](), 29th ISFN Annual Meeting
  
  
## Algorithmic Bias Control in Deep learning 1


Deep Learning (DL) has reached unparalleled performance in many domains. However, this impressive performance typically comes at the cost of gathering large datasets and training massive models, requiring extended time and prohibitive costs. Significant research efforts are being invested in improving DL training efficiency, i.e., the amount of time, data, and resources required to train these models, by changing the model (e.g., architecture, numerical precision) or the training algorithm (e.g., parallelization). Other modifications aim to address critical issues, such as credibility and over-confidence, which hinder the implementation of DL in the real world. However, such modifications often cause an unexplained degradation in the generalization performance of DL to unseen data. Recent findings suggest that this degradation is caused by changes to the hidden algorithmic bias of the training algorithm and model. This bias selects a specific solution from all solutions which fit the data. After years of trial-and-error, this bias in DL is often at a "sweet spot" which implicitly allows ANNs to learn well, due to unknown key design choices. But performance typically degrades when these choices change. Therefore, understanding and controlling algorithmic bias is the key to unlocking the true potential of deep learning.

Our goal is to develop a rigorous theory of algorithmic bias in DL and to apply it to alleviate critical practical bottlenecks that prevent such models from scaling up or implemented in real-world applications.

Our approach has three objectives: (1) identify the algorithmic biases affecting DL; (2) understand how these biases affect the functional capabilities and generalization performance; and (3) control these biases to alleviate critical practical bottlenecks. To demonstrate the feasibility of this challenging project, we describe how recent advances and concrete preliminary results enable us to effectively approach all these objectives.

### All related Research in the frame of this project:
The sign * indicates equal contribution of the authors.

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.ERC == 1 %}

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



**This project has received funding from the European Union’s Horizon Europe research and innovation programme under grant agreement No 101039436-ERC-A-B-C-Deep.**


<figure class="fourth">
 <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/ERC_logoHor.JPG" style="width: 610px">
</figure>





