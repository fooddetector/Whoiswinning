Our team's project (website) is called *Who's winning?*
The website consists of three main pages: (1) The primary 'Homepage' where the user can select indicators (out of a list of 13 hard and soft power indicators) of their choice and see results based on it; (2) An 'Our Team' page; (3) A 'Data Sources' page giving details of all the indicators and their data sources
The file-system is organized such that all the files for a particular page are within the same directory/sub-directory of that page's index.html
Each page has its own separate CSS file and the javascript files used to code the relevant functionalities on that page
For eg: For the Homepage, the main HTML file (index.html) is in the main directory. The directory also consists of sytles.css used to style all elements page. The main.js has the D3 js code for the quiz and barchart functions, whereas map.js is for the choropleth map and navigation.js is for the navigation bar. The map.js uses the countries.geojson file to populate the map. Data on all the indicators is stores in whoiswinning.csv
The sub-directory for Our Team page is named as 'our-team' and for Data Sources page it is 'data-source'