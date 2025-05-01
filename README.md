# Wild Clay in the Greater NYC Area

Used SSURGO soil survey data to map clay-rich soil deposits in the tristate area near New York City.
Map can be viewed [here](https://psychicautomaton.quarto.pub/clay_map/).

Note that in order to run clay_maps.qmd you first have to create the clay.gpkg using the code in clay_data.Rmd. 
Currently, it is set up so you have to manually open the ssurgo_portal (code included in clay_data)
and create the table with ratings for % clay, but I'm hoping to automate that as well.  

The map background uses a custom mapbox style that can be previewed [here](https://api.mapbox.com/styles/v1/psychicautomaton/cma4f3hku005p01qw86dv8sca.html?title=view&access_token=pk.eyJ1IjoicHN5Y2hpY2F1dG9tYXRvbiIsImEiOiJjbWE0ZjJuaXUwNjZzMmxweXlzcDN5OGQ5In0.Yme9yPL4rt8OuuySLUOYqg&zoomwheel=true&fresh=true#2/38/-34_).