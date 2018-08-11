

11-classwork is the Foundations file with the first shape files and waffle house csv we used when learning QGIS

TO DO:
-highlight the states with certain number of solar gardens in the map
-TRY TO MAP A HEX GRID MAP WITH HEAT FOR PLACES PRODUCING THE MOST SOLAR-GARDEN POWER
-RESEARCH CALIFORNIA TO SEE WHETHER THERE ARE NEW SOLAR GARDENS THERE TO ADD TO MY DF:
https://news.energysage.com/community-solar-gardens-sharing-the-sun/

http://www.startribune.com/minnesota-s-solar-garden-program-takes-off-in-2017/464428133/

-EXPLORE geogiffy or switching to Leaflet


WOULD BE NICE: use time manager qgis plug in to do a geogiffy showing the lights coming on as time goes on and solar gardens are made (watch the solar gardens grow)
https://medium.com/@tjukanov/geogiffery-in-a-nutshell-introduction-to-qgis-time-manager-31bb79f2af19

****SOMA'S PAGE WITH HELPFUL REMINDERS ON HOW TO USE QGIS:
https://gist.github.com/jsoma/0865246bd9223a6b86fe6876efb4c640

WaPo inspiration:
https://www.washingtonpost.com/graphics/national/power-plants/?utm_term=.0a9a89b4f867



-HOW TO EXPORT TO PNG OR SOMETHING USEABLE IN MARYANNE'S TEMPLATE WITH QGIS:
--> "New Print Layout" button (4th from the left on top of QGIS; it's in bet disk icon with green bit and the piece of paper with a wrench icon)
	--> give it a title in first small pop up box and click OK
		--> in big window that pops up, select area for the image by clicking the 'add a new map to the layout' button (it's a piece of paper with green +, 6th from the top); with tht selected, start at top left of 'artboard' like layout and drag to define area (I just did the whole thing or close to it); when you let go from the click and drag, the image you're trying to export should appear
			--> can use select (hand at top left) to manipulate the image as needed (zoom, move around, etc)
				--> from LAYOUT menu at the top dropdown, select 'Export as image'
					--> give it a name, navigate to where you want it, make sure it's type you want (png) and click save




good background reading
https://www.vox.com/2015/7/29/9066685/coal-oil-solar-maps

links that might be useful:
SEIA press release about solar growth:
https://www.seia.org/news/us-solar-market-adds-25-gw-pv-q1-2018-growing-13-year-over-year

2012 NREL report on potential of renewables:
https://openei.org/doe-opendata/dataset/5346c5c2-be26-4be7-9663-b5a98cbb7527/resource/01fe78a8-77b6-4c59-bc36-cae177ee86c3/download/usretechpotential.pdf




How many community 'solar gardens' are there in the US?

How have they grown over time?

Where are they?

Could use the other data set that expresses potential of energy sources; think the estimate for community solar was small but might be interesting to look at.

Could even poke around a bit more and try to find db of rooftop solar and compare with community.


data sets:
United States Renewable Energy Technical Potential (csv)
https://catalog.data.gov/dataset/united-states-renewable-energy-technical-potential/resource/5f1c6aae-3cb3-45bd-83ce-0ada52e25074

Solar Energies Industry Assoc
"About":
The Solar Energy Industries Association (SEIA®) is the driving force behind solar energy and is building a strong solar industry to power America through advocacy and education. As the national trade association of the U.S. solar energy industry, which now employs more than 250,000 Americans, we represent all organizations that promote, manufacture, install and support the development of solar energy. SEIA works with its 1,000 member companies to build jobs and diversity, champion the use of cost-competitive solar in America, remove market barriers and educate the public on the benefits of solar energy.


link for the NREL db of solar gardens: https://openei.org/datasets/dataset/community-solar-project-databas2/resource/f0000000-58cc-4372-a567-000000000095
PRIMARY DATASET (NREL) VARIABLE DESCRIPTIONS
Variable descriptions								
Project Name	Project name, if applicable							

City	City where system is sited							

State	State							

Utility	Utility service territory							

System Size (kW)	System capacity in kilowatts. Most project capacities should represent rated capacity in kilowatts DC, but errors may exist.							

Year of Interconnection	Estimated year that project began serving customers.							

Co-located Projects	Some community solar arrays are co-located components of a larger project. If applicable, this field reflects  a single project name to link such co-located projects.		

Ciy Lat	Latitude of the city where the project is located (latitude does not represent the location of the project, but may be used as a rough approximation of project location for the purposes of geographic visuals)							
City Long	Longitude of the city where the project is located (latitude does not represent the location of the project, but may be used as a rough approximation of project location for the purposes of geographic visuals)							
