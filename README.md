D3-County-Map
=============


## Install

Since this is simply a static html page I'm just using `http-server` to display the page:

````
npm i http-server 
````

Install all the dependecies (d3, topojson):

````
npm i
````

Build the `us.json` file to power the map:

````
make us.json
````

Launch the server

````
http-server -p 8008
````

Navigate your browser to: http://localhost:8008
