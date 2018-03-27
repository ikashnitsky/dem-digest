---
layout: article
permalink: /about-en
title: "About the project"
author: ilya
---

***

*Demographic Digest*  is a regular column at [Demoscope Weekly](http://demoscope.ru) which publishes (in Russian) brief summaries of fresh demographic papers from the best academic journals.  

The aim of the project is to present notable demographic papers of our western colleagues to Russian speaking audience. We do not strive to cover all the results and the methodological nuances of the reviewed papers. In some reviews, the interest drives our attention to the small details that might seem insignificant to the reader, while the other reviews may seem rather sketchy. To resolve any additional questions concerning the papers covered in Digest, the reader is invited to investigate the original publications. The presented reviews are no more than just one possible way of reading the academic texts. 

**[The archive of Demographic Digest at Demoscope Weekly](http://demoscope.ru/weekly/arc/arcdigest.php)**  


***

# Demographic Review

Selected reviews from *Demographic Digest* are reprinted in Russian academic journal *[Demographic Review](https://demreview.hse.ru/en/)* and are in open access. Below are the links to all publications of Demographic Digest in *Demographic Review*, in **year-issue** format.  


|------------------|------------------|------------------|------------------|
|                  |                  | [[2015-3][153]]  | [[2015-4][154]]  |
| [[2016-1][161]]  | [[2016-2][162]]  | [[2016-3][163]]  | [[2016-4][164]]  |
| [[2017-1][171]]  | [[2017-2][172]]  | [[2017-3][173]]  |                  |
| [[2018-1][181]]  |                  |                  |                  |

[153]: https://demreview.hse.ru/2015--3/174844051.html
[154]: https://demreview.hse.ru/2015--4/179986337.html
[161]: https://demreview.hse.ru/2016--1/185829684.html
[162]: https://demreview.hse.ru/2016--2/190973840.html
[163]: https://demreview.hse.ru/2016--3/196886615.html
[164]: https://demreview.hse.ru/2016--4/202163189.html
[171]: https://demreview.hse.ru/2017--1/206925692.html
[172]: https://demreview.hse.ru/2017--2/210565796.html
[173]: https://demreview.hse.ru/2017--3/212768468.html
[181]:


***

# Participation of HSE students

Since 2016 *Demographic Digest* welcomes contributions from  from external authors. In February 2017 the first [project](https://www.hse.ru/org/hse/pfair/199751652.html) for the students of National Research University Higher School of Economics was launched.


<ul>
  {% for author in 
  [maria-vilkova, anna-levina, julia-lonshchikova, olesya-kliushina] 
  %}
    {% assign author = site.data.authors[author] %}
    <div class="author-image">
	<img src="{{ site.url }}/images/{{ author.avatar }}" alt="{{ author.name }}">
</div><!-- ./author-image -->
<div class="author-content">
	<h3 class="author-name" >{% if author.web %}<a href="{{ author.web }}" itemprop="author">{{ author.name }}</a>{% else %}<span itemprop="author">{{ author.name }}</span>{% endif %}</h3>
	<p class="author-bio">{{ author.bio }}</p>
</div><!-- ./author-content -->
  {% endfor %}
</ul>

|------------------|--------------------------------------------------------|
|                  |                                                        |