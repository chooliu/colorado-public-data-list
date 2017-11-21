# colorado-public-data-list

**A curated list of public datasets for Colorado.**

The most thorough sources of Coloradoan open data sources are the Open Colorado data catalog ([data.opencolorado.org](http://data.opencolorado.org)) and the Colorado Information Marketplace ([data.colorado.gov](https://data.colorado.gov)).

However, there are many other sources of public data that may not meet the formal definition of "open data" (namely, machine-readable, API-ready CKAN/Socrata-formats; see the [Sunlight Foundation](https://sunlightfoundation.com/opendataguidelines/) guidelines). Alternatively, the data may not be from an official government source (not included in the above portals). 

**This repo documents public Colorado data sources (that may or may not be "open"), as well as promote citizen-led attempts at making public data more open (see "Citizen-Wrangled Data" header).** It is not intended to be comprehensive, but rather serve as a launchpad for data science for social good/civic hacking project ideas.

Note: There's many fantastic federal data sources like [data.gov](http://data.gov), the [USGS](https://www.usgs.gov) for spatial data, and [censusreporter.org](https://censusreporter.org) that contain Colorado data can't be thoroughly listed here (maybe in a future iteration). OpenDataSoft's collection of [open data portals worldwide](https://www.opendatasoft.com/a-comprehensive-list-of-all-open-data-portals-around-the-world/) is also inspiring.


## Official State Organizations

| Site | Owner | Notes | Format |
|:----|:---|:---|:---|
| Colorado's Decision Support Systems | [cdss.state.co.us/onlineTools](http://cdss.state.co.us/onlineTools/Pages/OtherData.aspx) | agricultural and livestock yields, as well as some of the water resources data of the Depart of Natural Resources described below.  | search query -> pdf, csv |
| Colorado Department of Natural Resources | [water.state.co.us/DataMaps](http://water.state.co.us/DataMaps/DataSearch/Pages/DataSearch.aspx) | groundwater monitoring and maps, water rights, climate stations. | search query |
| Colorado Environmental Public Health Tracking| [coepht.dphe.state.co.us](http://www.coepht.dphe.state.co.us/)| longitudinal disease surveillance data, as well as some environmental data (ozone, particulate matter levels, oil and gas concerns). | search query -> Google drive tables |
| Colorado Health and Environmental Data | [cohealthdata.dphe.state.co.us](https://www.cohealthdata.dphe.state.co.us) | similar to above, but notably more social indicators (social determinants of health, food poisoning, marijuana usage) and some additional diseases | search query -> Google drive tables |
| Oil and Gas Conservation Commission |  [cogcc.state.co.us](http://cogcc.state.co.us)  | well permits, production rates, locations, spills. also see [airwatergas.org](http://airwatergas.org) for scrapes of limited "open data" versions. | search queries -> PowerBI tables |
|Colorado Transparency Online Project | [colorado.gov/apps/oit/transparency](https://www.colorado.gov/apps/oit/transparency/index.html) | grants, budget, revenue/expenses by fiscal year; also see "Resources" tab | search query -> excel table |
|Colorado Data Marketplace | [data.colorado.gov](http://data.colorado.gov) | official State of Colorado open data portal. highly recommended. ⭐ | Socrata portal |
|Colorado Department of Education | [cde.state.co.us/schoolview](https://www.cde.state.co.us/schoolview) | enrollment, test scores, outcomes, administration info for schools | xls, search query, cognos |
| Colorado Department of Public Health and Environment |  [data-cdphe.opendata.arcgis.com](http://data-cdphe.opendata.arcgis.com) | goespatial data (boundaries, surveillance, demographics) from the CDPHE | ArcGIS Portal |
| Colorado Department of Revenue | [colorado.gov/pacific/revenue/statistics](http://colorado.gov/pacific/revenue/statistics) |  tax revenue (e.g. gambling, marijuana, sales, income) and expenditure reports | excel, pdf |
| Department of Local Affairs / Demography Office | [demography.dola.colorado.gov/data](http://demography.dola.colorado.gov/data)| population, demographics, jobs/labor force, housing projections; miscellaneous GIS files | csv, shapefiles |
| Colorado Department of Transportation |[dtdapps.coloradodot.info/otis](http://dtdapps.coloradodot.info/otis) | roads, highways, other transportation structures; traffic counts and accidents | csv, pdf, shapefiles |
| LexisNexis | [lexisnexis.com/hottopics/colorado](http://lexisnexis.com/hottopics/colorado) | hosts Colorado Constitution, Revised Statues, Court Rules | HTML |
| Colorado GeoData Cache | [geodata.co.gov](https://geodata.co.gov/) | large elevation, satellite images, LIDAR files following 2013 floods | search query -> shapefiles, tif |
| Secretary of State |  [sos.state.co.us](http://sos.state.co.us) | lists of businesses, charities, and lobbyists; miscellaneous elections, fundraising, and voting information | search query, xls |

## Non-Profit / Miscellaneous Organizations

| Site | Owner | Notes | Format |
|:----|:---|:---|:--|
| AirWaterGas| [data.airwatergas.org](https://data.airwatergas.org/) | NSF-funded project scraping oil & gas industry data (including Colorado Oil and Gas Conservation Commission) and delivering open, readable formats | csv |
| ArcGIS Hub | [hub.arcgis.com/datasets?q=colorado](http://hub.arcgis.com/datasets?q=colorado) | as many cities and counties use ArcGIS to host data, a geography-based search on ArcGIS Hub will pulls up many of these datasets | ArcGIS Portal |
| Colorado Health Institute | [coloradohealthinstitute.org/data](http://coloradohealthinstitute.org/data) | health insurance, health workforce (e.g., location of certified counselors), health surveys, access to care; county health profiles | xlsx, Tableau |
| Data USA | [datausa.io/profile/geo/colorado](http://datausa.io/profile/geo/colorado) | Datawheel, Deloitte, MIT Media Lab effort to visualize data public gov't data across US (use to find federal sources of interest) | D3plus, API downloads |
|Denver Regional Council of Governments | [gis.drcog.org/datacatalog/](http://gis.drcog.org/datacatalog) | emphasis on visualization; Denver Regional Aerial Photography Project; job force, transit, land use, urban development |  csv, shapefiles |
| Shift Research Lab | [denvermetrodata.org](http://denvermetrodata.org) |  aggregates various federal (census/American Community Survey) and local county/city datasets by neighborhood, tract, custom regions; great visualizations | "report builder" search query > csv |
| OpenColorado | [data.opencolorado.org](http://data.opencolorado.org) | awesome volunteer / non-profit catalog of open data in Colorado. highly recommended. ⭐ | CKAN |
|Regional Transportation District | [rtd-denver.com/Developer.shtml](http://rtd-denver.com/Developer.shtml) | real time schedule data, transit routes/stop locations | GTFS API, shapefiles |
|University of Colorado System | [cu.edu/budgetpolicy/accountability-data-center](http://www.cu.edu/budgetpolicy/accountability-data-center)| budget, institutional research information for the UC campuses | csv, search query|

## County Organizations

| Owner/County | Site | Notes | Format |
|:----|:---|:---|:---|
| Douglas County| [data.douglas.co.us](http://data.douglas.co.us) | budget, elections, GIS, transportation and outdoors |Socrata portal|
| Jefferson County | [jeffco.us/open](http://jeffco.us/open/) | employee salaries, budget; zoning, housing, development projects; citizen surveys, community safety | search query, pdf |
|Routt County | [data-routtgis.opendata.arcgis.com](http://data-routtgis.opendata.arcgis.com/) | assessor table, zoning, precincts, roads |ArcGIS portal|
|Larimer County | [larimer.org](http://www.larimer.org/) | see "public records" tab: property records/taxes/sales, foreclosures, food safety inspections | search query |

## City Organizations

Note: The [Colorado Municipal League](https://www.cml.org/cml-member-directory/) has links to websites for the majority of the nearly 300 cities & towns in Colorado -- each of these websites may also have more public data of interest.

| Site | Owner/City | Notes | Format|
|:----|:---|:---|:---|
|Arvada | [arvada.org/city-hall/transparency/opendata](http://arvada.org/city-hall/transparency/opendata) |  |  shapefiles, pdf |
|Aspen| [mapaspen-cityofaspen.opendata.arcgis.com](http://mapaspen-cityofaspen.opendata.arcgis.com/)| | ArcGIS portal |
|Aurora |  [apps2.auroragov.org/opendata](https://apps2.auroragov.org/opendata/) | |xlsx, shapefiles|
|Denver |  [denvergov.org/opendata](https://www.denvergov.org/opendata) | |csv, shapefiles, pdf |
|Boulder |  [bouldercolorado.gov/open-data](https://bouldercolorado.gov/open-data) | |json, shapefiles, csv|
|Broomfield |  [opendata.broomfield.org](http://opendata.broomfield.org/) | | shapefiles |
|Thornton | [data-cityofthornton.opendata.arcgis.com](http://data-cityofthornton.opendata.arcgis.com) | |ArcGIS portal|




# Citizen-Wrangled Data

Below are some open-source Github projects that we know of trying to make Colorado data more open.

Feel free to get in touch or submit an Github issue if (1) you have a project wrangling Colorado data, or (2) have a recommendation on what public data to wrangle next / want to work together on something!

## Completed Projects
| Owner | Site | Notes |
|:----|:---|:---|
| OpenElections.org| [github.com/openelections](https://github.com/openelections/openelections-data-co) | Colorado election results by county, precinct, district (state and federal levels)|

## On-Going Projects

| Owner | Site | Notes |
|:----|:---|:---|
| @chooliu | [colorado-environmental-records-scraper](https://github.com/chooliu/colorado-environmental-records-scraper) | scraping permit violations / Title V records from CDHPE |
| @chipoglesby | [larimerCountyRestaurantInspections](https://github.com/chipoglesby/larimerCountyRestaurantInspections)| scraping food inspections from Larimer County |
