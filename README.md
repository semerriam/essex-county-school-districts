# Essex County, Mass. Public School Districts

Project can be seen in its current form [here.](https://semerriam.github.io/pj_ec_schools.html)

This project focuses on the demographic and educational attainment differences between public school districts in Essex County and the distances between these districts. The two-week exploration of primarily [Mass. DOE](https://profiles.doe.mass.edu/state_report/), [NCES](https://nces.ed.gov/ccd/schoolsearch/school_list.asp?Search=1&DistrictID=2506660/), and [ACS](https://www.census.gov/quickfacts/) data required merging over 20 datasets and using a variety of tools to analyze and explore the data graphically. Highlights included looking into [historical documents](https://books.google.com/books?id=dc9ygP8aoS0C&pg=PA87&lpg=PA87&dq=%E2%80%9Cthe+racial+balance+in+all+citywide+schools+shall+be+reflective+of+the+total+student+population+in+the+Boston+Public+School+system,+with+a+5+percent+leeway+in+white+or+minority+enrollments.+For+example,+white+students+represent+51+percent+of+the+city%E2%80%99s+student,+so+white+enrollment+could+number+from+56+to+46+percent+at+any+citywide+school.+Black+and+other+minority+students,+who+are+49+percent+of+the+city%E2%80%99s+total+school+enrollment,+may+range+from+54+to+44+percent+of+enrollment+at+individual+citywide+schools.%E2%80%9D&source=bl&ots=MbLuoeScuY&sig=ACfU3U18zuk8VRN21Pd9r1y5LFlgseRaDw&hl=en&sa=X&ved=2ahUKEwjhz5Cqj-71AhWIT98KHZb3AN0Q6AF6BAgCEAM#v=onepage&q=%E2%80%9Cthe%20racial%20balance%20in%20all%20citywide%20schools%20shall%20be%20reflective%20of%20the%20total%20student%20population%20in%20the%20Boston%20Public%20School%20system%2C%20with%20a%205%20percent%20leeway%20in%20white%20or%20minority%20enrollments.%20For%20example%2C%20white%20students%20represent%2051%20percent%20of%20the%20city%E2%80%99s%20student%2C%20so%20white%20enrollment%20could%20number%20from%2056%20to%2046%20percent%20at%20any%20citywide%20school.%20Black%20and%20other%20minority%20students%2C%20who%20are%2049%20percent%20of%20the%20city%E2%80%99s%20total%20school%20enrollment%2C%20may%20range%20from%2054%20to%2044%20percent%20of%20enrollment%20at%20individual%20citywide%20schools.%E2%80%9D&f=false) about busing in the 70's and learning how to calculate and code the Haversine formula. Additionally, historical data aggregated by the [Boston Regional Metropolitan Planning Organization](https://www.ctps.org/node/3280/) was used to compare incomes between towns. 

Some tools used:
- Python — Pandas, plotnine
- R - ggplot
- Excel
- HTML
- Google API
- QGIS - OSM 
- Datawrapper
- RAWGraphs
- Illustrator



This repository holds several sub-folders devoted to different areas of the project:

## Essex County School Distances Repository
This sub-folder features a notebook, [essex_county_school_distances.ipynb](ec_school_distances/essex_county_school_distances.ipynb) that calculates the distance between each high school location using the Haversine formula with gps coordinates and joins the locations with each town name of residents attending each high school.

## Essex County School Data Repository
This sub-folder features two notebooks: The notebook, [essex_county_public_schools_data.ipynb](ec-school-data/essex_county_public_schools_data.ipynb) merges datasets from the Massachusetts Department of Education (DOE) and U.S. Census Bureau data for school districts and towns in Essex County. [essex_county_public_schools_two_towns.ipynb](ec-school-data/essex_county_public_schools_two_towns.ipynb) compares this data to the distances between school district locations. 

## Essex County School Graphics Repository
This sub-folder features a notebook, [essex_county_public_schools_graphs.ipynb](ec_school_graphics/essex_county_public_schools_graphs.ipynb) that graphically explores the combination of demographic, educational, and distance data— continuing what began in the two towns notebook. 

![essex-country-school-districts-combos.png](ec_school_graphics/essex-country-school-districts-combos.png)

## Essex County School Districts Google Maps API Repository
This sub-folder includes a html document, [ec_schools_google_maps_api_copy.html](ec-school-districts-google-maps-api/ec_schools_google_maps_api_copy.html), which uses the Google Maps API (with the key removed) to plot the school district locations.

## Essex County School Districts Busing Scenarios Repository
This sub-folder includes the data used for calculating school district busing scenarios in three school district clusters.

### Licensing
All code in this repository is available under the [MIT License](https://opensource.org/licenses/MIT). Files in the output/ directory are available under the [Creative Commons Attribution 4.0 International (CC BY 4.0) license](https://creativecommons.org/licenses/by/4.0/).
