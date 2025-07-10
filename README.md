# Dead Forest Burning



**Title:** Dead Forests Burning



**Description:**

This repository contains code and supporting items central to the story map link below. The composition of this site serves as a final project for class: Geovisualization provided by Oregon State University.

This [story map](https://taluccia.github.io/beetlefire/index.html) visualizes maps, data, and images about how forest burn when wildfire is preceded by substantial tree mortality events from bark beetle outbreaks.


**Technical summary:**

- In this repository there is an image file with a sample of photos
- Aerial video footage might be available
- Some field data could potentially be integrated
- Remote sensing analysis from google earth engine platform (see file GEE_sample)
- Spatial data could include: fire perimeters, provincial park boundaries, biogeoclimatic zones, tree species (spatial data file only includes fire perimeters for now)

**Group Members:**

- Michael Cook
- Dominique Bachelet
- Anna Talucci

**Interface Sketch:**


![Alt Text](https://github.com/taluccia/geog4572.proposal.taluccia/blob/master/images/sketchpg1.JPG?raw=true)
![Alt Text](https://github.com/taluccia/geog4572.proposal.taluccia/blob/master/images/sketchpg2.JPG?raw=true)
![Alt Text](https://github.com/taluccia/geog4572.proposal.taluccia/blob/master/images/sketchpg3.JPG?raw=true)  



### Design Scheme

#### Layout

We used a story map layout



#### Color Scheme

We generated our color scheme using a photograph in coolors.co

 

![image color](img/aerialphoto1.png)







Then used coolors.com.

**[Color Scheme](https://coolors.co/acc4dd-39381a-59584f-bfb085-757f92)**

![color scheme from coolors](img/coolorpalette.png)



### Data Source

- Beetle Outbreak Aerial Survey data from **[Data BC](https://data.gov.bc.ca/)**
- Landsat Data from the USGS processed in Google Earth Engine
- Photographs: from field data by Anna Talucci
- Favicon: a combination of fab fa-gripfire and fas fa-bug that were acquired from https://fontawesome.com/icons
- Tree Species data from the Vegetation Resource Inventory acquired from **[Data BC](https://data.gov.bc.ca/)**
- Fire perimeters and Provincial Parks Boundaries acquired from **[Data BC](https://data.gov.bc.ca/)**




### Applied Libraries

We used a variety of existing libraries including style sheets and scripts

Style sheets: 

```html
<!--add required stylesheets-->
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.3.1/dist/leaflet.css"/>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<!--boostrap-->

<!--leaflet css-->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet/1.3.1/leaflet.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.5.2/animate.min.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.12/css/all.css">
<link rel="stylesheet" href="https://turban.github.io/Leaflet.Photo/examples/lib/cluster/MarkerCluster.css" />
<link rel="stylesheet" href="https://turban.github.io/Leaflet.Photo/Leaflet.Photo.css" />



<!--Fonts-->
<link href="https://fonts.googleapis.com/css?family=Source+Sans+Pro" rel="stylesheet">
<link rel="stylesheet" href="css/main.css" />
<link rel="stylesheet" type="text/css" href="css/storymap.2.4.css">
```

Scripts:

```html
<!--Scripts-->
<!--add required libraries-->
<script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet/1.3.1/leaflet.js"></script>
<!--jquery-->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.0/umd/popper.min.js"></script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<!--boostrap-->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.0/js/bootstrap.min.js"></script>

<script src="js/leaflet.markercluster-src.js"></script>
<script src="https://turban.github.io/Leaflet.Photo/Leaflet.Photo.js"></script>


<!--leaflet.ajax for asynchronously adding geojson data-->
<script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet-ajax/2.1.0/leaflet.ajax.min.js"></script>

<!--story map plugin-->
<script src="js/storymap.2.4.js"></script>

<script src="js/data.js"></script>

<script src="https://d3js.org/d3.v4.min.js"></script>
```



### Credits

- Geographic Data: Fire Perimeters, Outbreak Severity, Provincial Parks acquired from **[https://data.gov.bc.ca/](Data BC)**
- Remote Sensing Data: Landsat Data from <a href="https://landsat.usgs.gov/">USGS</a> and processed in **[https://earthengine.google.com/](Google Earth Engine)**
- Context: Peer reviewed research, field work, and analyses
- Photos: Theodore Temperli, Anna Talucci
- Favicon: a combination of fab fa-gripfire and fas fa-bug that were acquired from https://fontawesome.com/icons
- Graph data: Wulder et al. 2009
- Video: Adobe Spark Software used to produce Launch Page photo slide show



### Acknowledgements

We would like to thank Dr. Bo Zhao for comments, assistance, and editorial advice.



### References

[1] Coops, N. C., M. a. Wulder, and J. C. White. 2006. Integrating remotelysensed and ancillary data sources to characterize a mountain pine beetleinfestation. Remote Sensing of Environment 105:83–97.

[2] Frazier, R. J., N. C. Coops, M. A. Wulder, T. Hermosilla, and J. C. White.2018. Analyzing spatial and temporal variability in short-term rates ofpost-fire vegetation return from Landsat time series. Remote Sensing ofEnvironment 205:32–45.

[3] Kennedy, R. E., Z. Yang, W. B. Cohen, E. Pfaff, J. Braaten, and P. Nelson.2012. Spatial and temporal patterns of forest disturbance and regrowth withinthe area of the Northwest Forest Plan. Remote Sensing of Environment122:117–133.

[4] Key, C. H., and N. C. Benson. 2006. Landscape assessment (LA): Samplingand analysis methods. USDA Forest Service General Technical ReportRMS-GTR-164-CD:1–55.

[5] Kurz, W. a, Dymond, C. C., Stinson, G., Rampley, G. J., Neilson, E. T., Carroll, a L., … Safranyik, L. (2008). Mountain pine beetle and forest carbon feedback to climate change. Nature, 452(April), 987–990. <https://doi.org/10.1038/nature06777>

[6] Meigs, G. W., R. E. Kennedy, and W. B. Cohen. 2011. A Landsat time seriesapproach to characterize bark beetle and defoliator impacts on tree mortalityand surface fuels in conifer forests. Remote Sensing of Environment115:3707–3718.

[7] Pickell, P. D., T. Hermosilla, R. J. Frazier, N. C. Coops, and M. A.Wulder. 2016. Forest recovery trends derived from Landsat time series for NorthAmerican boreal forests. International Journal of Remote Sensing 37:138–149.

[8] Roy, D. P., V. Kovalskyy, H. K. Zhang, E. F. Vermote, L. Yan, S. S. Kumar,and A. Egorov. 2016. Characterization of Landsat-7 to Landsat-8 reflectivewavelength and normalized difference vegetation index continuity. RemoteSensing of Environment 185:57–70.

[9] White, J. C., M. A. Wulder, T. Hermosilla, N. C. Coops, and G. W. Hobart.2017. A nationwide annual characterization of 25 years of forestdisturbance and recovery for Canada using Landsat time series. Remote Sensingof Environment 194:303–321.

[10] Wulder, M. a., C. C. Dymond, J. C. White, D. G. Leckie, and A. L. Carroll.2006. Surveying mountain pine beetle damage of forests: A review of remotesensing opportunities. Forest Ecology and Management 221:27–41.

[11] Wulder, M. A., White, J. C., Grills, D., Nelson, T., & Coops, N. C. (2009). Aerial overview survey of the mountain pine beetle epidemic in British Columbia: Communication of impacts. BC Journal of Ecosystems and Management, 10(1), 45–58.





