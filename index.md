
# Geospatial Data Explorers

The link to this page is [this](https://hmarvi.github.io/index.html)

## Selected websites out of 12

### Ocean Navigator [here](http://navigator.oceansdata.ca/public/)
### Integrated Ocean Observing System of U.S. accessible in [here](https://sensors.ioos.us/#map)
### Saint Lawrence Global Observatory asseccible at [here](https://test-www.ogsl.ca/en)
### State of Ocean by NASA assecible at [here](https://podaac-tools.jpl.nasa.gov/soto/#b=BlueMarble_ShadedRelief_Bathymetry&l=GHRSST_L4_MUR_Sea_Surface_Temperature(la=true),MODIS_Aqua_CorrectedReflectance_TrueColor,MODIS_Aqua_Chlorophyll_A,jpl_l4_mur_ssta___ssta___36000_x_18000___daynight&ve=-225,-54.0859375,-10,54.0859375&pl=false&pb=false&d=2019-11-29&ao=false&as=2019-11-22&ae=2019-11-29&asz=1/day&afr=500&tlr=days)


# Comparison and Evaluation of Selected Websites
| URL  | Back-end (server-side PL) | Front-end (client-side PL)  | Web-server | Content Management System | Widget | OS and severs  | Framework | Web-hosting provider  | Content delivery network | Analytics and tracking  | mapping | image file formats  | JS libraries | Other technologies  | Evaluation |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| http://navigator.oceansdata.ca/public/  | Python  | reactJS  | Gunicorn  | -  | -  | -  | -  | -  | StackPath BootstrapCDN  | -  | OpenLayers  | PNG | JQuery  | - | - |
| https://sensors.ioos.us/#map  | PHP  | JavaScript  | nginx  | -  | Font Awesome, Google Font API  | -  | CExpressJS  | Amazon  | GStatic Google Static Content Usage Statistics  | -  | Leaflet  | Not sure! (xhr request??!) | Backbone.js, Marionette, underscore, D3, Hogan  | Node.Js's frame work (ExpressJs)  | Best among these. Works both with hovering and clicking (sp less data is rendered on the fly). I like the hegxagons.  |
 https://test-www.ogsl.ca/octo/?mapextent=-7347086.392356057,6621293.722740165,5  | PHP  | JavaScript  | Apache | Drupal  | MailChimp, Font Awesome, ThemePunch  | - | -  | -  | -  | -  | -  | PNG, JPEG, bmp  | Hammer, JQuery, utilJS, Onion,JS,CommonJS  | OWL Carousel  | - |
| https://podaac-tools.jpl.nasa.gov/soto  | PHP  | JavaScript  | Apache | Drupal  | Sitelinks search box , Google tag manager  | Red Hat enterprise linux, Open SSL  | Amazon  | - | Amazon cloud front  | CrazyEgg  | Leaflet  | Content Cell  | html5shiv, Modernizr, jQuery, jQuery once,  jQuery UI, jQuery UI Tabs, Tablesorter | -  | -  |

## Sources: 
https://w3techs.com/
https://builtwith.com/

{: .my-class }
