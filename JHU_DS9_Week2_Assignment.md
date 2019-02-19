---
title: "Peer-graded Assignment: R Markdown and Leaflet"
author: "Robert A. Stevens"
date: '2019-02-18'
output:
  html_document:
    keep_md: yes
always_allow_html: yes
---



The *John Deere Global Technology Innovation Network* consists of seven Technology Innovation Centers (TICs) around the world:


```
     Abbr                   Name                Location
1    ATIC                   Asia             Pune, India
2    CTIC                  China          Tianjin, China
3    ETIC               European Kaiserslautern, Germany
4 JDTIC-A      John Deere - Ames           Ames, IA, USA
5 JDTIC-C John Deere - Champaign      Champaign, IL, USA
6   LATIC          Latin America      Indaiatuba, Brazil
7    MTIC                 Moline         Moline, IL, USA
```

Zoom in on the markers to see each location.

<!--html_preserve--><div id="htmlwidget-2b2676d853c2deaf9a48" style="width:1056px;height:816px;" class="leaflet html-widget"></div>
<script type="application/json" data-for="htmlwidget-2b2676d853c2deaf9a48">{"x":{"options":{"crs":{"crsClass":"L.CRS.EPSG3857","code":null,"proj4def":null,"projectedBounds":null,"options":{}}},"calls":[{"method":"addTiles","args":["//{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",null,null,{"minZoom":0,"maxZoom":18,"tileSize":256,"subdomains":"abc","errorTileUrl":"","tms":false,"noWrap":false,"zoomOffset":0,"zoomReverse":false,"opacity":1,"zIndex":1,"detectRetina":false,"attribution":"&copy; <a href=\"http://openstreetmap.org\">OpenStreetMap<\/a> contributors, <a href=\"http://creativecommons.org/licenses/by-sa/2.0/\">CC-BY-SA<\/a>"}]},{"method":"addMarkers","args":[[18.512806,39.077408,49.456145,41.998822,40.088962,-23.008051,41.476732],[73.92689,117.728238,7.801322,-93.638497,-88.23927,-47.117107,-90.420013],null,null,null,{"interactive":true,"draggable":false,"keyboard":true,"title":"","alt":"","zIndexOffset":0,"opacity":1,"riseOnHover":false,"riseOffset":250},["ATIC","CTIC","ETIC","JDTIC-A","JDTIC-C","LATIC","MTIC"],null,null,null,["ATIC","CTIC","ETIC","JDTIC-A","JDTIC-C","LATIC","MTIC"],{"interactive":false,"permanent":false,"direction":"auto","opacity":1,"offset":[0,0],"textsize":"10px","textOnly":false,"className":"","sticky":true},null]}],"limits":{"lat":[-23.008051,49.456145],"lng":[-93.638497,117.728238]}},"evals":[],"jsHooks":[]}</script><!--/html_preserve-->

Visit the [John Deere web page](https://www.deere.com/en/index.html) for more company information.
