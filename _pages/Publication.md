---
layout: single
title: "Publications"
permalink: /Pub/
toc: true
toc_sticky: true
---

# Summary and Key paper list
- Total number of papars: 40 (Main author papers: 9)
- H-index: 20 (from Google scholar, as of 2025.02.18)

1. **Toward Quantitative Electrodeposition via In Situ Liquid Phase Transmission Electron Microscopy: Studying Electroplated Zinc Using Basic Image Processing and 4D STEM** [[ref]](https://doi.org/10.1002/smtd.202400081)<br>
*Junbeom Park*, Sarmila Dutta, Hongyu Sun, Janghyun Jo, Pranav Karanth, Dieter Weber, Amir H. Tavabi, Yasin Emre Durmus, Krzysztof Dzieciol, Eva Jodat, André Karl, Hans Kungl, Yevheniy Pivak, H. Hugo Pérez Garza, Chandramohan George, Joachim Mayer, Rafal E. Dunin-Borkowski, Shibabrata Basak, Rüdiger-A. Eichel <br> Small Methods (2024) DOI:10.1002/smtd.202400081
1. **Titanium nitride microelectrode: a new candidate for in-situ electrochemical transmission electron microscopy study** [[ref]](https://doi.org/10.1002/adem.202302146)<br>
*Junbeom Park#*, Ningyan Cheng#, Binghui Ge, Yevheniy Pivak, Hongyu Sun, H. Hugo Pérez Garz, Shibabrata Basak, Rüdiger-A. Eichel <br> Advanced Engineering Materials (2024)DOI:10.1002/adem.202302146 (#: Equal contribution)
1. **Structural Study of Polyacrylonitrile-Based Carbon Nanofibers for Understanding Gas Adsorption** [[ref]](http://dx.doi.org/10.1021/acsami.1c13541)<br>
*Junbeom Park*, Ansgar Kretzschmar, Victor Selmert, Osmane Camara, Hans Kungl, Hermann Tempel, Shibabrata Basak, Rüdiger A. Eichel <br> ACS Applied Materials & Interfaces 13 (2021) 46665
1. **Mathematical model for the dynamic behavior of carbon nanotube yarn in analogy with hierarchically structured bio-materials** [[ref]](https://doi.org/10.1016/j.carbon.2019.05.077)<br>
*Junbeom Park*, Jaegeun Lee, Dong-Myeong Lee, Sung-Hyun Lee, Hyeon Su Jeong, Kun-Hong Lee, Seung Min Kim <br> Carbon 152 (2019) 151

# Journal papers
<ol>
{% for paper in site.data.Publication_list %}
  <li>
    <b>{{ paper.title }}</b> 
    <a href="https://doi.org/{{ paper.DOI }}"> [ref] </a> <br>

    {% for author in paper.author %}
        {% if author.family == "Park" and author.given == "Junbeom" %}
            <i> {{author.given}} {{author.family}} </i>,
        {% else %}
            {{author.given}} {{author.family}},
        {% endif %}
    {% endfor %}

    <br> {{ paper.container-title }} {{ paper.volume }} ({{ paper.year }}) {{ paper.page }} <br>
  </li>
{% endfor %}
</ol>

# Patents
1. **Apparatus for continuously producing carbon nanotubes** [[ref]](https://patents.google.com/patent/US11332372B2/en)<br>
Seung Min Kim, Sung Hyun Lee, *Jun Beom Park*, Ji Hong Park, Dong Myeong Lee, Sook Young Moon, Hyeon Su Jeong <br> US 11,332,372 B2, KR10-2019-0170412
1. **Method for continuous manufacture of CNTF having high strength and high conductivity** [[ref]](https://patents.google.com/patent/US10246333B1/en)<br>
Seung Min Kim, Hyeon Su Jeong, Jae Geun Lee, Dong Myeong Lee, Hun Su Lee, Young Kwan Kim, *Jun Beom Park* <br> US 10,246,333 B1, KR 10-1972987
1. **Apparatus for manufacturing CNT and Method of manufacturing CNT using the same** [[ref]](https://patents.google.com/patent/KR101981675B1/en)<br>
Seung Min Kim, Hanbin Park, Sook Young Moon, Hyeon Su Jeong, Young Kwan Kim, *Jun Beom Park* <br> KR 10-1981675
1. **Production method of high performance carbon nano tube/carbon composite fiber and carbon nanotube/carbon composite fiber thereby** [[ref]](https://patents.google.com/patent/KR101726823B1/en)<br>
Seung Min Kim, Jae Geun Lee, Dong Myeong Lee, *Jun Beom Park*, Jun Yeon Hwang, Hyeon Su Jeong <br> KR 10-1726823


# Presentations
## A. Seminars and Lectures

<ol>
{% for paper in site.data.Presentation_seminar %}
  <li>
    ({{paper.type}})  <b>{{ paper.title }}</b> <br>

    {% for author in paper.author %}
        {% if author.name == "Junbeom Park" %}
            <i> {{author.name}} </i>,
        {% else %}
            {{author.name}},
        {% endif %}
    {% endfor %}

    <br> {{ paper.location }} ({{ paper.year }}) {{ paper.city }} <br>
  </li>
{% endfor %}
</ol>

## B. Oral presentations at conferences
<ol>
{% for paper in site.data.Presentation_oral %}
  <li>
    <b>{{ paper.title }}</b> <br>

    {% for author in paper.author %}
        {% if author.name == "Junbeom Park" %}
            <i> {{author.name}} </i>,
        {% else %}
            {{author.name}},
        {% endif %}
    {% endfor %}

    <br> {{ paper.location }} ({{ paper.year }}) {{ paper.city }} <br>
  </li>
{% endfor %}
</ol>

## C. Poster presentations at conferences

<ol>
{% for paper in site.data.Presentation_poster %}
  <li>
    <b>{{ paper.title }}</b> <br>

    {% for author in paper.author %}
        {% if author.name == "Junbeom Park" %}
            <i> {{author.name}} </i>,
        {% else %}
            {{author.name}},
        {% endif %}
    {% endfor %}

    <br> {{ paper.location }} ({{ paper.year }}) {{ paper.city }} <br>
  </li>
{% endfor %}
</ol>