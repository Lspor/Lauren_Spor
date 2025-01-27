---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2016, 2017, 2018, 2019, 2020, 2021]
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

<div class="jumbotron">
### Publications



<p>

        <a href="https://scholar.google.com/citations?hl=en&user=94i9gpIAAAAJ&view_op=list_works&sortby=pubdate" target="_blank">Google Scholar profile</a><br />
        <a href="http://orcid.org/0009-0008-9587-8452" target="_blank">ORCiD</a><br />
{% for member in site.data.pi %}
{% if member.cv %} <a href="{{ site.url }}{{ site.baseurl }}/{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> <br /> {% endif %}
{% endfor %}        
</p>
</div>


<div class="jumbotron">
### Preprints
{% bibliography --query @unpublished %}
</div>

<div class="jumbotron">
### Recent refereed journal articles
{% bibliography --query @article %}
</div>

