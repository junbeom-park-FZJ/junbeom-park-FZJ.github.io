---
layout: single
title: "Publications"
permalink: /Pub/
toc: true
toc_sticky: true
---


# 1. Journal papers (40)
- H-index: 20 (from <a href="https://scholar.google.com/citations?user=WXKca60AAAAJ&hl=en">Google scholar</a>, as of 2025.02.18)
<ol>
{% for paper in site.data.Publication_list %}
  <li>
    <b>{{ paper.title }}</b> 
    <a href="https://doi.org/{{ paper.DOI }}"> [ref] </a> <br>

    {% for author in paper.author %}
        {% if author.family == "Park" and author.given == "Junbeom" %}
            <i><u> {{author.given}} {{author.family}}</u></i>,
        {% else %}
            {{author.given}} {{author.family}},
        {% endif %}
    {% endfor %}

    <br> {{ paper.container-title }} {{ paper.volume }} ({{ paper.year }}) {{ paper.page }} <br>
  </li>
{% endfor %}
</ol>

# 2. Patents (4)

1. **Apparatus for continuously producing carbon nanotubes** [[ref]](https://patents.google.com/patent/US11332372B2/en)<br>
Seung Min Kim, Sung Hyun Lee, <i><u>Jun Beom Park</u></i>, Ji Hong Park, Dong Myeong Lee, Sook Young Moon, Hyeon Su Jeong <br> US 11,332,372 B2, KR10-2019-0170412
1. **Method for continuous manufacture of CNTF having high strength and high conductivity** [[ref]](https://patents.google.com/patent/US10246333B1/en)<br>
Seung Min Kim, Hyeon Su Jeong, Jae Geun Lee, Dong Myeong Lee, Hun Su Lee, Young Kwan Kim, <i><u>Jun Beom Park</u></i> <br> US 10,246,333 B1, KR 10-1972987
1. **Apparatus for manufacturing CNT and Method of manufacturing CNT using the same** [[ref]](https://patents.google.com/patent/KR101981675B1/en)<br>
Seung Min Kim, Hanbin Park, Sook Young Moon, Hyeon Su Jeong, Young Kwan Kim, <i><u>Jun Beom Park</u></i> <br> KR 10-1981675
1. **Production method of high performance carbon nano tube/carbon composite fiber and carbon nanotube/carbon composite fiber thereby** [[ref]](https://patents.google.com/patent/KR101726823B1/en)<br>
Seung Min Kim, Jae Geun Lee, Dong Myeong Lee, <i><u>Jun Beom Park</u></i>, Jun Yeon Hwang, Hyeon Su Jeong <br> KR 10-1726823


# 3. Presentations
## A. Seminars and Lectures (6)

<ol>
{% for paper in site.data.Presentation_seminar %}
  <li>
    ({{paper.type}})  <b>{{ paper.title }}</b> <br>

    {% for author in paper.author %}
        {% if author.name == "Junbeom Park" %}
            <i><u> {{author.name}}</u></i>,
        {% else %}
            {{author.name}},
        {% endif %}
    {% endfor %}

    <br> {{ paper.location }} ({{ paper.year }}) {{ paper.city }} <br>
  </li>
{% endfor %}
</ol>

## B. Oral presentations at conferences (5)
<ol>
{% for paper in site.data.Presentation_oral %}
  <li>
    <b>{{ paper.title }}</b> <br>

    {% for author in paper.author %}
        {% if author.name == "Junbeom Park" %}
            <i><u> {{author.name}}</u></i>,
        {% else %}
            {{author.name}},
        {% endif %}
    {% endfor %}

    <br> {{ paper.location }} ({{ paper.year }}) {{ paper.city }} <br>
  </li>
{% endfor %}
</ol>

## C. Poster presentations at conferences (18)

<ol>
{% for paper in site.data.Presentation_poster %}
  <li>
    <b>{{ paper.title }}</b> <br>

    {% for author in paper.author %}
        {% if author.name == "Junbeom Park" %}
            <i> {{author.name}}</i>,
        {% else %}
            {{author.name}},
        {% endif %}
    {% endfor %}

    <br> {{ paper.location }} ({{ paper.year }}) {{ paper.city }} <br>
  </li>
{% endfor %}
</ol>