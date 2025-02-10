---
layout: single
title: "Publications"
permalink: /Pub/
toc: true
toc_sticky: true
---

# Summary and Key paper list
- Total number of papars: 38 (Main author papers: 9)
- H-index: 20 (from Google scholar, as of 2025.01.05)

1. **Toward Quantitative Electrodeposition via In Situ Liquid Phase Transmission Electron Microscopy: Studying Electroplated Zinc Using Basic Image Processing and 4D STEM** [[ref]](https://doi.org/10.1002/smtd.202400081)<br>
*Junbeom Park*, Sarmila Dutta, Hongyu Sun, Janghyun Jo, Pranav Karanth, Dieter Weber, Amir H. Tavabi, Yasin Emre Durmus, Krzysztof Dzieciol, Eva Jodat, André Karl, Hans Kungl, Yevheniy Pivak, H. Hugo Pérez Garza, Chandramohan George, Joachim Mayer, Rafal E. Dunin-Borkowski, Shibabrata Basak, Rüdiger-A. Eichel | Small Methods (2024) DOI:10.1002/smtd.202400081
1. **Titanium nitride microelectrode: a new candidate for in-situ electrochemical transmission electron microscopy study** [[ref]](https://doi.org/10.1002/adem.202302146)<br>
*Junbeom Park#*, Ningyan Cheng#, Binghui Ge, Yevheniy Pivak, Hongyu Sun, H. Hugo Pérez Garz, Shibabrata Basak, Rüdiger-A. Eichel | Advanced Engineering Materials (2024)DOI:10.1002/adem.202302146 (#: Equal contribution)
1. **Structural Study of Polyacrylonitrile-Based Carbon Nanofibers for Understanding Gas Adsorption** [[ref]](http://dx.doi.org/10.1021/acsami.1c13541)<br>
*Junbeom Park*, Ansgar Kretzschmar, Victor Selmert, Osmane Camara, Hans Kungl, Hermann Tempel, Shibabrata Basak, Rüdiger A. Eichel | ACS Applied Materials & Interfaces 13 (2021) 46665
1. **Mathematical model for the dynamic behavior of carbon nanotube yarn in analogy with hierarchically structured bio-materials** [[ref]](https://doi.org/10.1016/j.carbon.2019.05.077)<br>
*Junbeom Park*, Jaegeun Lee, Dong-Myeong Lee, Sung-Hyun Lee, Hyeon Su Jeong, Kun-Hong Lee, Seung Min Kim | Carbon 152 (2019) 151

# Journal papers
<ol>
{% for paper in site.data.Publication_list %}
  <li>
    <b>{{ paper.title }}</b> 
    <a href="https://doi.org/{{ paper.DOI }}"> [ref] </a> <br>

    {% for author in paper.author %}
        {% if author.family == "Park" and author.given == "Junbeom" %}
            <i> {{author.given}} {{author.family}} </i> ,
        {% else %}
            {{author.given}} {{author.family}} ,
        {% endif %}
    {% endfor %}

    | {{ paper.container-title }} {{ paper.volume }} ( {{ paper.year }} ) {{ paper.page }} <br>
  </li>
{% endfor %}
</ol>

# Patents
1. **Apparatus for continuously producing carbon nanotubes** [[ref]](https://patents.google.com/patent/US11332372B2/en)<br>
Seung Min Kim, Sung Hyun Lee, *Jun Beom Park*, Ji Hong Park, Dong Myeong Lee, Sook Young Moon, Hyeon Su Jeong | US 11,332,372 B2, KR10-2019-0170412
1. **Method for continuous manufacture of CNTF having high strength and high conductivity** [[ref]](https://patents.google.com/patent/US10246333B1/en)<br>
Seung Min Kim, Hyeon Su Jeong, Jae Geun Lee, Dong Myeong Lee, Hun Su Lee, Young Kwan Kim, *Jun Beom Park* | US 10,246,333 B1, KR 10-1972987
1. **Apparatus for manufacturing CNT and Method of manufacturing CNT using the same** [[ref]](https://patents.google.com/patent/KR101981675B1/en)<br>
Seung Min Kim, Hanbin Park, Sook Young Moon, Hyeon Su Jeong, Young Kwan Kim, *Jun Beom Park* | KR 10-1981675
1. **Production method of high performance carbon nano tube/carbon composite fiber and carbon nanotube/carbon composite fiber thereby** [[ref]](https://patents.google.com/patent/KR101726823B1/en)<br>
Seung Min Kim, Jae Geun Lee, Dong Myeong Lee, *Jun Beom Park*, Jun Yeon Hwang, Hyeon Su Jeong | KR 10-1726823


# Presentations
## A. Seminars and Lectures
1. (Seminar) **Strength measurement of Material**<br>
*Junbeom Park*<br>
VeKNI (The Korean Scientists and Engineers Association in Germany) Material division Workshop, 2024, Aachen, Germany
1. (Seminar) **Toward Live processing on in-situ TEM**<br>
*Junbeom Park*<br>
VeKNI (The Korean Scientists and Engineers Association in Germany) Region 5 Workshop, 2024, Aachen, Germany
1. (Lecture) **Semiconductor analysis equipment (Ch.x Advanced STEM, Ch.x in-situ TEM)**<br>
*Junbeom Park*<br>
Semiconductor Process and Equipment Contract department, Pusan National University (PNU), 2024, Busan, Korea
1. (Seminar) **The impact of data processing on material research**<br>
*Junbeom Park*<br>
Institute of Advanced Composite Materials, Korea Institute of Science and Technology (KIST) Jeonbuk, 2023, Wanju, Korea
1. (Seminar) **In-situ transmission electron microscopy**<br>
*Junbeom Park*<br>
VeKNI (The Korean Scientists and Engineers Association in Germany) Region 5 Workshop, 2023, Aachen, Germany
1. (Seminar) **Accurate measurement of linear density via Favimat+**<br>
*Junbeom Park*<br>
Institute of Advanced Composite Materials, Korea Institute of Science and Technology (KIST) Jeonbuk, 2017, Wanju, Korea

## B. Oral presentations at conferences
1. **Utilizing Data Processing for Enhanced Material Characterization**<br>
*Junbeom Park*<br>
VeKNI (The Korean Scientists and Engineers Association in Germany) 2024 conference, 2024, Essen, Germany
1. **In-situ Transmission Electron Microscopy and Image Processing**<br>
*Junbeom Park*, Hongyu Sun, Janghyun Jo, Shibabrata Basak, Rüdigar-A. Eichel<br>
Europe-Korea Conference on Science and Technology 2023 (EKC2023), 2023, Munich, Germany
1. **FIB-based lamella preparation for in-situ TEM gas experiment**<br>
*Junbeom Park*, Osmane Camara, Hermann Tempel, Hans Kungl, Shibabrata Basak, Rüdigar-A. Eichel<br>
16th Multinational Congress on Microscopy, 2022, Brno, Czech Republic
1. **Theoretical model for structure determination of hierarchically structured carbon nanotube yarn**<br>
*Junbeom Park*, Jaegeun Lee, Sung-Hyun Lee, Kun-Hong Lee and Seung Min Kim<br>
Carbon 2018 World Conference, 2018, Madrid, Spain
1. **Proper linear density measurement method of hierarchical structural carbon nanotube fibers by vibroscope**<br>
*Junbeom Park*, Sung-Hyun Lee, Jaegeun Lee, Dong-Myeong Lee, Seung Min Kim and Kun-Hong Lee<br>
2016 spring meeting of the Korean Carbon Society, 2016, Gumi, Korea

## C. Poster presentations at conferences
### Period 2020s
1. **Development of simple image processing for in-situ TEM toward live processing**<br>
*Junbeom Park*, Hongyu Sun, Janghyun Jo, Eva Jodat, André Karl, Shibabrata Basak, Rüdigar-A.Eichel<br>
EMC2024, 2024, Copenhagen, Denmark
1. **Data processing of in-situ TEM toward live processing**<br>
*Junbeom Park*, Hongyu Sun, Janghyun Jo, Eva Jodat, André Karl, Shibabrata Basak, Rüdigar-A.Eichel<br>
PICO2024, 2024, Vaals, Netherlands
1. **Improving the knowledge from in-situ Liquid Phase TEM via image processing**<br>
*Junbeom Park*, Hongyu Sun, Janghyun Jo, Shibabrata Basak, Rüdigar-A. Eichel<br>
The 20th International Microscopy Congress (IMC20), 2023, Busan, Korea
1. **Understanding gas adsorption of PAN-based carbon nanofibers**<br>
*Junbeom Park*, Ansgar Kretzschmar, Victor Selmert, Osmane Camara, Hans Kungl, Hermann Tempel, Shibabrata Basak, Rüdigar-A. Eichel<br>
PICO 2022, 2022, Kasteel Vaalsbroek, The Netherlands

### Period 2010s
1. **Mathematical model for dynamic mechanical behavior of carbon nanotube yarns in analogy with hierarchically structured bio-materials**<br>
*Junbeom Park*, Jaegeun Lee, Dong-Myeong Lee, Sung-Hyun Lee, Hyeon Su Jeong, Kun-Hong Lee and Seung Min Kim
2019 spring meeting of the Korean Carbon Society, 2019, Daegu, Korea
1. **The effect of weak oxidant on the synthesis of carbon nanotube fiber**<br>
*Junbeom Park*, Hanbin Park, Sung-Hyun Lee and Seung Min Kim<br>
2018 spring meeting of the Korean Carbon Society, 2018, Gwangju, Korea
1. **Effect of Water on Synthesis of Carbon Nanotube by Floating Catalyst Method**<br>
*Junbeom Park*, Hanbin Park, Jaegeun Lee, Dong-Myeong Lee and Seung Min Kim<br>
The 23rd Nanotube research group, 2018, Muju, Korea
1. **The effect of spinning rate during the fabrication of carbon nanotube fibers**<br>
*Junbeom Park*, Jaegeun Lee, Hanbin Park, Dong-Myeong Lee, Kun-Hong Lee and Seung Min Kim<br>
2017 spring meeting of the Korean Carbon Society, 2017, Changwon, Korea
1. **Characterization of carbon nanotube fibers from the hierarchical viewpoint**<br>
*Junbeom Park*, Jaegeun Lee, Dong-Myeong Lee, Hanbin Park, Kun-Hong Lee and Seung Min Kim<br>
2017 spring meeting of KIChE, 2017, Jeju, Korea
1. **The effect of carrier gas flow rate on properties of carbon nanotube fibers**<br>
*Junbeom Park*, Sung-Hyun Lee, Seung Min Kim and Kun-Hong Lee<br>
China NANO 2015, 2015, Bejing, China
1. **The effect of carrier gas flow rate on the synthesis of CNT fibers by direct spinning method**<br>
*Junbeom Park*, Sung-Hyun Lee, Jinseok Kim, Seung Min Kim and Kun-Hong Lee<br>
2015 spring meeting of the Korean Carbon Society, 2015, Gumi, Korea
1. **The effect of sulfur and IR heating on the carbon nanotube (CNT) fibers**<br>
*Junbeom Park*, Sung-Hyun Lee, Jinseok Kim, Seojeong Jeong, Seung Min Kim and Kun-Hong Lee<br>
2014 fall meeting of the Korean Carbon Society, 2014, Jeonju, Korea
1. **The effect of thiophene concentration during synthesizing the carbon nanotube (CNT) fibers**<br>
*Junbeom Park*, Sung-Hyun Lee, Seojeong Jeong, Jinseok Kim, Seung Min Kim and Kun-Hong Lee<br>
2014 Fall meeting of KIChE, 2014, Daejeon, Korea
1. **Surface analysis of carbon nanotube (CNT) yarns after acid treatment**<br>
*Junbeom Park*, Sung-Hyun Lee and Kun-Hong Lee<br>
2013 fall meeting of the Korean Carbon Society, 2013, Jeonju, Korea
1. **Acid treatment on synthesized carbon nanotube yarns from methane**<br>
*Junbeom Park*, Sung-Hyun Lee and Kun-Hong Lee<br>
2013 Fall meeting of KIChE, 2013, Daegu, Korea
1. **Dipping carbon nanotube (CNT) yarns in various acids for chemical treatment**<br>
*Junbeom Park*, Sung-Hyun Lee and Kun-Hong Lee<br>
2013 Spring meeting of the Korean Carbon Society, 2013, Seoul, Korea
1. **Changes of carbon nanotube (CNT) yarns surface after acid treatment**<br>
*Junbeom Park*, Sung-Hyun Lee and Kun-Hong Lee<br>
2013 Spring conference of the Korean Fiber Society, 2013, Daegu, Korea
1. **Purification of carbon nanotube (CNT) fibers with acid treatment**<br>
*Junbeom Park*, Sung-Hyun Lee and Kun-Hong Lee<br>
2013 KIChE winter season workshop, 2013, Muju, Korea
