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

<ul>
{% for paper in site.data.Publication_list %}
  <li>
    <b>{{ paper.title }}</b> 
    <a href="https://doi.org/{{ paper.DOI }}"> [ref] </a> <br>

    {% for author in {{ paper.author }} %}
        {% if {{ author.family == "Park" }} & {{ author.given == "Junbeom" }} %}
            <i> {{author.given}} {{author.family}} </i> ,
        {% else %}
            {{author.given}} {{author.family}} ,
        {% endif %}
    {% endfor %}

    | {{ paper.container-title }} {{ paper.volume }} {{ paper.issued.year }} {{ paper.page }} <br>
  </li>
{% endfor %}
</ul>


# Journal papers
## Period 2020s
1. **Titanium nitride microelectrode: a new candidate for in-situ electrochemical transmission electron microscopy study** [[ref]](https://doi.org/10.1002/adem.202302146)<br>
*Junbeom Park#*, Ningyan Cheng#, Binghui Ge, Yevheniy Pivak, Hongyu Sun, H. Hugo Pérez Garz, Shibabrata Basak, Rüdiger-A. Eichel | Advanced Engineering Materials (2024)DOI:10.1002/adem.202302146 (#: Equal contribution)
1. **Towards quantitative electrodeposition via in-situ liquid phase Transmission Electron Microscopy: Studying Electroplated Zinc using Basic Image Processing and 4D STEM** [[ref]](https://doi.org/10.1002/smtd.202400081)<br>
*Junbeom Park*, Sarmila Dutta, Hongyu Sun, Janghyun Jo, Pranav Karanth, Dieter Weber, Amir H. Tavabi, Yasin Emre Durmus, Krzysztof Dzieciol, Hans Kungl, Yevheniy Pivak, H. Hugo Pérez Garza, Chandramohan George, Joachim Mayer, Rafal E. Dunin-Borkowski, Shibabrata Basak, Rüdiger-A. Eichel | Small Methods (2024) DOI:10.1002/smtd.202400081
1. **High-resolution and analytical electron microscopy in a liquid flow cell via gas purging** [[ref]](https://doi.org/10.1093/jmicro/dfad023)<br>
Yevheniy Pivak#, *Junbeom Park#*, Shibabrata Basak, Rüdiger-Albert Eichel, Anne Beker, Alejandro Rozene, Héctor Hugo Pérez Garza, Hongyu Sun | Microscopy 72 (2023) 520 (#: Equal contribution)
1. **Structural Study of Polyacrylonitrile-Based Carbon Nanofibers for Understanding Gas Adsorption** [[ref]](http://dx.doi.org/10.1021/acsami.1c13541)<br>
*Junbeom Park*, Ansgar Kretzschmar, Victor Selmert, Osmane Camara, Hans Kungl, Hermann Tempel, Shibabrata Basak, Rüdiger A. Eichel | ACS Applied Materials & Interfaces 13 (2021) 46665
1. **Deep-injection floating-catalyst chemical vapor deposition to continuously synthesize carbon nanotubes with high aspect ratio and high crystallinity** [[ref]](https://doi.org/10.1016/j.carbon.2020.11.065)<br>
Sung-Hyun Lee#, *Junbeom Park#*, Ji Hong Park#, Dong-Myeong Lee#, Anna Lee, Sook Young Moon, Sei Young Lee, Hyeon Su Jeong, Seung Min Kim | Carbon 173 (2021) 901 (#: Equal contribution)
1. **Improving mechanical and physical properties of ultra-thick carbon nanotube fiber by fast swelling and stretching process** [[ref]](http://doi.org/10.1016/j.carbon.2020.10.068)<br>
Dong-Myeong Lee#, *Junbeom Park#*, Jaegeun Lee, Sung-Hyun Lee, Shin-Hyun Kim, Seung Min Kim, Hyeon Su Jeong | Carbon 172 (2021) 733 (#: Equal contribution)

1. **Effect of Low Environmental Pressure on Sintering Behavior of NASICON-Type Li1.3Al0.3Ti1.7(PO4)3 Solid Electrolytes: An In Situ ESEM Study** [[ref]](https://doi.org/10.1021/acs.cgd.2c01098)<br>
Osmane Camara, Qi Xu, *Junbeom Park*, Shicheng Yu, Xin Lu, Krzysztof Dzieciol, Roland Schierholz, Hermann Tempel, Hans Kungl, Chandramohan George, Joachim Mayer, Shibabrata Basak, and Rüdiger-A. Eichel | Crystal Growth & Design 23 (2023) 1522
1. **Screening of Coatings for an All-Solid-State Battery using In Situ Transmission Electron Microscopy** [[ref]](https://dx.doi.org/10.3791/64316)<br>
Shibarata Basak, *Junbeom Park*, Janghyun Jo, Osmane Camara, Amir H. Tavabi, Hermann Tempel, Hans Kungl, Chandramohan George, Rafal E. Dunin-Borkowski, Joachim Mayer,Rüdiger-A. Eichel | Journal of Visualized Experiments 191 (2023) e64316
1. **Active Interphase Enables Stable Performance for an All-Phosphate-Based Composite Cathode in an All-Solid-State Battery** [[ref]](https://doi.org/10.1002/smll.202200266)<br>
Qi Xu, Zigeng Liu, Anna Windmüller, Shibabrata Basak, *Junbeom Park*, Krzysztof Dzieciol, Chih-Long Tsai, Shicheng Yu, Hermann Tempel, Hans Kungl, Rüdiger-A. Eichel | Small 18 (2022) 202200266
1. **Purification effect of carbon nanotube fibers on their surface modification to develop a high-performance and multifunctional nanocomposite fiber** [[ref]](https://doi.org/10.1016/j.carbon.2020.11.026)<br>
Young-Kwan Kim, Young-Jin Kim, *Junbeom Park*, Sang Woo Han, Seung Min Kim | Carbon 173 (2021) 376
1. **Strong and Highly Conductive Carbon Nanotube Fibers as Conducting Wires for Wearable Electronics** [[ref]](https://doi.org/10.1021/acsanm.1c00248)<br>
Sung-Hyun Lee, *Junbeom Park*, Sook Young Moon, Sei Young Lee, Seung Min Kim | ACS Applied Nano Materials 4 (2021) 3833
1. **Continuous synthesis of high-crystalline carbon nanotubes by controlling the configuration of the injection part in the floating catalyst chemical vapor deposition process** [[ref]](https://doi.org/10.1007/s42823-020-00131-3)<br>
Ji Hong Park, *Junbeom Park*, Sung-Hyun Lee, Seung Min Kim | Carbon Letter 30 (2020) 613
1. **Different thermal degradation mechanisms: Role of aluminum in Ni-rich layered cathode materials** [[ref]](https://doi.org/10.1016/j.nanoen.2020.105367)<br>
Eunmi Jo, Jae-Ho Park, *Junbeom Park*, Jieun Hwang, Kyung Yoon Chung, Kyung-Wan Nam, Seung Min Kim, Wonyoung Chang | Nano Energy 78 (2020) 105367

## Period 2010s
1. **Mathematical model for the dynamic behavior of carbon nanotube yarn in analogy with hierarchically structured bio-materials** [[ref]](https://doi.org/10.1016/j.carbon.2019.05.077)<br>
*Junbeom Park*, Jaegeun Lee, Dong-Myeong Lee, Sung-Hyun Lee, Hyeon Su Jeong, Kun-Hong Lee, Seung Min Kim | Carbon 152 (2019) 151
1. **Accurate measurement of specific tensile strength of carbon nanotube fibers with hierarchical structures by vibroscopic method** [[ref]](https://doi.org/10.1039/C6RA26607J)<br>
*Junbeom Park*, Sung-Hyun Lee, Jaegeun Lee, Dong-Myeong Lee, Hayoung Yu, Hyeon Su Jeong, Seung Min Kim, Kun-Hong Lee | RSC Advances 7 (2017) 8575
1. **Carbon nanotube yarns** [[ref]](https://doi.org/10.1007/s11814-012-0016-1)<br>
*Junbeom Park*, Kun-Hong Lee | Korean Journal of Chemical Engineering 29 (2012) 277
1. **Bio-inspired incorporation of functionalized graphene oxide into carbon nanotube fibers for their efficient mechanical reinforcement** [[ref]](https://doi.org/10.1016/j.compscitech.2019.107680)<br>
Young-Jin Kim, *Junbeom Park*, Cheol-Min Yang, Hyeon Su Jeong, Seung Min Kim, Sang Woo Han, Beomjoo Yang, Young-Kwan Kim | Composite Science and Technology 181 (2019)
107680
1. **Direct spinning and densification method for high-performance carbon nanotube fibers** [[ref]](https://doi.org/10.1038/s41467-019-10998-0)<br>
Jaegeun Lee, Dong-Myeong Lee, Yeonsu Jung, *Junbeom Park*, Hun Su Lee, Young-Kwan Kim, Chong Rae Park, Hyeon Su Jeong, Seung Min Kim | Nature Communications 10 (2019) 2962
1. **Rationally designed catalyst layers toward “immortal” growth of carbon nanotube forests: Fe-ion implanted substrates** [[ref]](https://doi.org/10.1016/j.carbon.2019.06.030)<br>
Cheol-Hun Lee, Jaegeun Lee, *Junbeom Park*, Eunyoung Lee, Seung Min Kim, Kun-Hong Lee | Carbon 152 (2019) 482
1. **A seed-mediated growth of gold nanoparticles inside carbon nanotube fibers for fabrication of multifunctional nanohybrid fibers with enhanced mechanical and electrical properties** [[ref]](https://doi.org/10.1039/C8NR10446H)<br>
Young-Jin Kim, *Junbeom Park*, Hyeon Su Jeong, Min Park, Seulki Baik, Dong Su Lee, Heesuk Rho, Hyungjun Kim, Joong Hee Lee, Seung-Min Kim, Young-Kwan Kim | Nanoscale 11 (2019) 5295
1. **CNT bundle-based thin intracochlear electrode array** [[ref]](https://doi.org/10.1007/s10544-019-0384-y)<br>
Gwang Jin Choi, Tae Mok Gwon, Doo Hee Kim, *Junbeom Park*, Seung Min Kim, Seung Ha Oh, Yoonseob Lim, Sang Beom Jun, Sung June Kim | Biomedical Microdevices 21 (2019) 27
1. **Simultaneous enhancement of mechanical and electrical properties of carbon nanotube fiber by infiltration and subsequent carbonization of resorcinol-formaldehyde resin** [[ref]](https://doi.org/10.1016/j.compositesb.2018.12.132)<br>
Young-Jin Kim, *Junbeom Park*, Hyungjun Kim, Hyeon Su Jeong, Joong Hee Lee, Seung Min Kim, Young-Kwan Kim | Composite Part B: Engineering 163 (2019) 431
1. **Synthesis mechanism of carbon nanotube fibers using reactor design principles** [[ref]](https://doi.org/10.1016/j.ces.2018.07.041)<br>
Sung-Hyun Lee, Hye-Rim Kim, Haemin Lee, Jinwoo Lee, Cheol-Hun Lee, Jaegeun Lee, *Junbeom Park*, Kun-Hong Lee | Chemical Engineering Science 192 (2019) 431
1. **Improved Mechanical and Electrical Properties of Carbon Nanotube Yarns by Wet Impregnation and Multi-ply Twisting** [[ref]](https://doi.org/10.1007/s12221-018-8140-0)
Yu Ri Lee, *Junbeom Park*, Youngjin Jeong, Jong S. Park | Fibers and Polymers 19 (2018) 2478<br>
1. **Hierarchical structure of carbon nanotube fibers, and the change of structure during densification by wet stretching** [[ref]](https://doi.org/10.1016/j.carbon.2018.04.071)<br>
Hyunjung Cho, Haemin Lee, Eugene Oh, Sung-Hyun Lee, *Junbeom Park*, Hyun Jin Park, Suk-Bae Yoon, Cheol-Hun Lee, Gye-Hoon Kwak, Won Jae Lee, Juhan Kim, Ji Eun Kim, Kun-Hong Lee | Carbon 136 (2018) 409
1. **Metal nanofibrils embedded in long free-standing carbon nanotube fibers with a high critical current density** [[ref]](https://doi.org/10.1038/s41427-018-0028-3)<br>
Hokyun Rho, Min Park, Mina Park, *Junbeom Park*, Jiyoon Han, Aram Lee, Sukang Bae, Tae-Wook Kim, Jun-Seok Ha, Seung Min Kim, Dong Su Lee, Sang Hyun Lee | NPG Asia Materials 10 (2018) 146
1. **Effects of Wet-Pressing and Cross-Linking on the Tensile Properties of Carbon Nanotube Fibers** [[ref]](https://doi.org/10.3390/ma11112170)<br>
Hyunjung Cho, Jinwoo Lee, Haemin Lee, Sung-Hyun Lee, *Junbeom Park*, Cheol-Hun Lee, Kun-Hong Lee | Materials 11 (2018) 2170
1. **Photoacoustic effect on the electrical and mechanical properties of polymer-infiltrated carbon nanotube fiber/graphene oxide composites** [[ref]](https://doi.org/10.1016/j.compscitech.2017.10.014)<br>
Ki-Ho Nam, Yong-O. Im, Hye Jin Park, Haena Lee, *Junbeom Park*, Sunho Jeong, Seung Min Kim, Nam-Ho You, Jae-Hak Choi, Haksoo Han, Kun-Hong Lee, Bon-Cheol Ku | Composites Science and Technology 153 (2017) 136
1. **Synthesis of carbon nanotube fibers from carbon precursors with low decomposition temperatures using a direct spinning process** [[ref]](https://doi.org/10.1016/j.carbon.2017.08.064)<br>
Sung-Hyun Lee, Hye-Rim Kim, Taeseon Lee, Haemin Lee, Jinwoo Lee, Jaegeun Lee, *Junbeom Park*, Kun-Hong Lee | Carbon 124 (2017) 219
1. **Utilization of carboxylic functional groups generated during purification of carbon nanotube fiber for its strength improvement** [[ref]](https://doi.org/10.1016/j.apsusc.2016.09.060)<br>
Yong-O. Im, Sung-Hyun Lee, Teawon Kim, *Junbeom Park*, Jaegeun Lee, Kun-Hong Lee | Applied Surface Science 392 (2017) 342
1. **Synthesis of carbon nanotube fibers using the direct spinning process based on Design of Experiment (DOE)** [[ref]](https://doi.org/10.1016/j.carbon.2016.01.034)<br>
Sung-Hyun Lee, *Junbeom Park*, Hye-Rim Kim, Taeseon Lee, Jaegeun Lee, Yong-O. Im, Cheol-Hun Lee, Hyunjung Cho, Hyeseon Lee, Chi-Hyuck Jun, Yu-Chan Ahn, In-Beum Lee, Kun-Hong Lee | Carbon 100 (2016) 647
1. **High-strength carbon nanotube/carbon composite fibers via chemical vapor infiltration** [[ref]](https://doi.org/10.1039/C6NR06479E)<br>
Jaegeun Lee, Teawon Kim, Yeonsu Jung, Kihoon Jung, *Junbeom Park*, Dong-Myeong Lee, Hyeon Su Jeong, Jun Yeon Hwang, Chong Rae Park, Kun-Hong Lee, Seung Min Kim | Nanoscale 8 (2016) 18972
1. **Effects of a SiO2 sub-supporting layer on the structure of a Al2O3 supporting layer, formation of Fe catalyst particles, and growth of carbon nanotube forests** [[ref]](https://doi.org/10.1039/C6RA12250G)<br>
Jaegeun Lee, Cheol Hun Lee, *Junbeom Park*, Dong-Myeong Lee, Kun-Hong Lee, Sae Byeok Jo, Kilwon Cho, Benji Maruyama, Seung Min Kim | RSC Advances 6 (2016) 68424
1. **Improving the tensile strength of carbon nanotube yarn via one-step double [2+1] cycloadditions** [[ref]](https://doi.org/10.1007/s11814-015-0140-9)<br>
Hee Jin Kim, Jaegeun Lee, Byungrak Park, Jeong-Hoon Sa, Alum Jung, Teawon Kim, *Junbeom Park*, Woonbong Hwang, Kun-Hong Lee | Korean Journal of Chemical Engineering 33
(2016) 299
1. **The influence of boundary layer on the growth kinetics of carbon nanotube forests** [[ref]](https://doi.org/10.1016/j.carbon.2015.05.080)<br>
Jaegeun Lee, Eugene Oh, Teawon Kim, Jeong-Hoon Sa, Sung-Hyun Lee, *Junbeom Park*, Dustin Moon, In Seok Kang, Myung Jong Kim, Seung Min Kim, Kun-Hong Lee | Carbon 93 (2015) 217
1. **Synthesis of high-quality carbon nanotube fibers by controlling the effects of sulfur on the catalyst agglomeration during the direct spinning process** [[ref]](https://doi.org/10.1039/C5RA04691B)<br>
Sung-Hyun Lee, *Junbeom Park*, Hye-Rim Kim, Jaegeun Lee, Kun-Hong Lee | RSC Advances 5 (2015) 41894
1. **(Korean) Enhancement of the Mechanical Properties of CNT Fibers Synthesized by Direct Spinning Method with Various Post-Treatments** [[ref]](https://doi.org/10.7234/composres.2015.28.4.239)<br>
Jin-seok Kim, *Junbeom Park*, Seung Min Kim, L. K. Kwac, Jun Yeon Hwang | Composites Research 28 (2015) 239
1. **The reason for an upper limit to the height of spinnable carbon nanotube forests** [[ref]](https://doi.org/10.1007/s10853-013-7494-3)<br>
Jaegeun Lee, Eugene Oh, Hye-Jin Kim, Seungho Cho, Teawon Kim, Sunghyun Lee, *Junbeom Park*, Hee Jin Kim, Kun-Hong Lee | Journal of Materials Science 48 (2013) 6897

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
