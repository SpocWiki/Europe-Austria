---
aliases:
  - Tyrol
  - Tirol
location:
  - 47.3
  - 11.1
type: State
tags:
  - geo/State
dv_has_name: Tirol
dv_is_a_:
  - "[[../../../../../Geography/Place|Place]]"
  - "[[../../../../../Geography/Place/Administrative_Area/State|State]]"
has_id_wikidata: Q153809
hist_area_km2:
  475: 17.739
  500: 39.506
  525: 53.353
  550: 55.265
  575: 68.966
  600: 66.209
  625: 72.568
  650: 86.882
  675: 76.762
  700: 65.553
  725: 69.965
  750: 76.228
  775: 89.654
  800: 94.665
  825: 110.576
  850: 118.786
  875: 115.5
  900: 111.539
  925: 123.424
  950: 118.75
  975: 131.359
  1000: 129.066
  1025: 127.735
  1050: 131.162
  1075: 138.658
  1100: 141.951
  1125: 143.647
  1150: 145.956
  1175: 151.774
  1200: 152.4
  1225: 151.808
  1250: 153.028
  1275: 156.696
  1300: 157.738
  1325: 158.508
  1350: 161.263
  1375: 165.28
  1400: 165.735
  1425: 165.41
  1450: 167.238
  1475: 164.342
  1500: 166.805
  1525: 165.311
  1550: 167.839
  1575: 164.991
  1600: 161.246
  1625: 164.49
  1650: 164.342
  1675: 162.243
  1700: 163.454
  1725: 162.265
  1750: 160.081
  1775: 161.219
  1800: 161.799
  1825: 163.572
  1850: 159.591
  1875: 162.57
  1900: 158.895
  1925: 159.817
  1950: 156.736
  1975: 155.122
  2000: 153.249
  2025: 154.536
  2050: 151.995
  2075: 151.362
  2100: 149.291
  2125: 150.153
  2150: 148.494
  2175: 147.147
  2200: 145.749
  2225: 143.517
  2250: 140.23
  2275: 140.687
  2300: 136.854
  2325: 134.504
  2350: 132.248
  2375: 127.98
  2400: 126.663
  2425: 122.539
  2450: 120.314
  2475: 120.221
  2500: 114.17
  2525: 111.599
  2550: 108.342
  2575: 106.342
  2600: 100.971
  2625: 95.718
  2650: 92.075
  2675: 86.3
  2700: 84.498
  2725: 77.04
  2750: 72.155
  2775: 67.104
  2800: 62.391
  2825: 57.856
  2850: 52.913
  2875: 49.547
  2900: 45.256
  2925: 43.001
  2950: 40.125
  2975: 36.786
  3000: 33.111
  3025: 31.927
  3050: 27.893
  3075: 26.028
  3100: 22.729
  3125: 21.353
  3150: 19.128
  3175: 18.029
  3200: 15.436
  3225: 13.195
  3250: 10.791
  3275: 8.923
  3300: 7.112
  3325: 5.896
  3350: 4.794
  3375: 3.924
  3400: 3.054
  3425: 2.316
  3450: 1.419
  3475: 0.999
  3500: 0.68
  3525: 0.536
  3550: 0.261
  3575: 0.26
  3600: 0.174
  3625: 0.174
  3650: 0.145
---

# [[Tirol]] 

#is_/same_as :: [[WD~Tyrol,153809]]

[StateId::] 
isDeleted: false
confidential: public

## #has_/map  

```leaflet
id: Tirol
zoomFeatures: false 
defaultZoom: 8
minZoom: 4 
maxZoom: 18
geojsonFolder: ./Tirol//
markerFolder: ./Tirol/
markerFile: [[Tirol]] 
coordinates: [[Tirol]] 
```


name = `=this.dv_has_name` 
[CountryId::] 
#is_a_/Place  
is_a_ = `=this.dv_is_a_`
[has_place_longitude::] 
[has_place_latitude::] 
[Population::] 


### Area by Elevation 


```dataviewjs
await dv.view("_orga/JS/SparkLine", { histogram: dv.current().hist_area_km2
, scale: "lin"
, minRow: 0
, maxRow: 20
, widthFrom : "all"
});
```



```dataviewjs
dv.view("_orga/JS/Histogram", {
value: dv.current().hist_area_km2
, scale: "lin", width: 60
, minRow: 0
, maxRow: 20
, widthFrom : "all"
});
```



## #has_/text_of_/abstract 

> Tyrol ( tih-ROHL, ty-ROHL, TY-rohl; historically the Tyrole; 
> German: **Tirol** [tiˈroːl] ; Italian: Tirolo) 
> is a historical region in the Alps of Northern Italy and western Austria. 
> 
> The area was historically the core of the County of Tyrol, 
> part of the Holy Roman Empire, Austrian Empire and Austria-Hungary, 
> from its formation in the 12th century until 1919. 
> 
> In 1919, following World War I and the dissolution of Austria-Hungary, 
> it was divided into two modern administrative parts 
> through the Treaty of Saint-Germain-en-Laye:
> 
> State of Tyrol: 
> Formed through the merger of North and East Tyrol, as part of Austria.
> 
> Region of Trentino-Alto Adige: At that time still with Souramont (Cortina d'Ampezzo, Livinallongo del Col di Lana and Colle Santa Lucia) and the municipalities Valvestino, Magasa, and Pedemonte. This was seized in 1918 by the Kingdom of Italy, and since 1946 has been part of the Italian Republic.
> 
> With the founding of the European region Tyrol-South Tyrol-Trentino, the area has had its own legal entity since 2011. It is known as  a European Grouping for Territorial Cooperation.
>
> [Wikipedia](https://en.wikipedia.org/wiki/Tyrol)   


## Confidential Links & Embeds: 

### #is_/same_as :: [[/_Standards/Earth/Continent/Europe/Europe~Central/Austria/Austrias_States/Tirol|Tirol]] 

### #is_/same_as :: [[/_public/Earth/Continent/Europe/Europe~Central/Austria/Austrias_States/Tirol.public|Tirol.public]] 

### #is_/same_as :: [[/_internal/Earth/Continent/Europe/Europe~Central/Austria/Austrias_States/Tirol.internal|Tirol.internal]] 

### #is_/same_as :: [[/_protect/Earth/Continent/Europe/Europe~Central/Austria/Austrias_States/Tirol.protect|Tirol.protect]] 

### #is_/same_as :: [[/_private/Earth/Continent/Europe/Europe~Central/Austria/Austrias_States/Tirol.private|Tirol.private]] 

### #is_/same_as :: [[/_personal/Earth/Continent/Europe/Europe~Central/Austria/Austrias_States/Tirol.personal|Tirol.personal]] 

### #is_/same_as :: [[/_secret/Earth/Continent/Europe/Europe~Central/Austria/Austrias_States/Tirol.secret|Tirol.secret]] 

