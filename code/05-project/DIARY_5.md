
https://mattrehbein.github.io/SolarGardens/

THE STORY NEEDS:
-a kickass kicker
-a comparison to roof-top solar -- try to find dataset on for proj 7
-more on cali -- call their public utilities commission
-call NREL contact about a rooftop numbers -- and to ask when the comm solar db was updated last, more detail on how that info is collected/ weigh reliability
-how much electricity are these gardens making? graphs on this
-research more on how many homes can be powered by. Finish this sentence: "The most powerful garden pumps out about 5,700 kilowatts, enough to power roughly XXX homes."
-visit a garden -- there's nine, I think, in GA. Athens, Monroe
-flesh out the Cali stuff, and link to the green tech media article if don't get someone on record myself


FOR THE TEXT LEADING INTO THE ANIMATED MAP:
There were six solar gardens in the US in 2008. Here's how they grew over the next decade:

<a href="https://www.greentechmedia.com/articles/read/a-rough-start-possible-reforms-for-californias-community-solar-program#gs.bOYl=6U">Greentech Media</a>

DRAFT NOTES
Solar Gardens: A Blooming Trade
Solar Gardens: A Going -- and Growing -- Concern


The authors of the NREL database stiplate that it may not be at all times comprehensive. At first glance 

TO DO:
-set up webpage folder/file infrastructure
-create individual dataframes by year and save them each to csv so can make individual year maps for geogiffy

FOR PART II OF THIS PROJECT:
-TRY TO MAP A HEX GRID MAP WITH HEAT FOR PLACES PRODUCING THE MOST SOLAR-GARDEN POWER
-RESEARCH CALIFORNIA TO SEE WHETHER THERE ARE NEW SOLAR GARDENS THERE TO ADD TO MY DF:
https://news.energysage.com/community-solar-gardens-sharing-the-sun/
-make city mapper of MA
-make geogiffy of MA


**RESEARCH**
NREL page on community solar:
https://www.nrel.gov/technical-assistance/community-solar.html

on Cali: California Public Utilities Commission contact to ask whether there are any community solar projects up and running in the state:
-For questions about the GTSR program, please contact Cherie Chan at cherie.chan@cpuc.ca.gov or (415) 703-1779.

California Public Utilities Commission gov page on renewables program:
http://www.cpuc.ca.gov/General.aspx?id=12181

PGE page on developing community solar projects/developers
https://www.pge.com/en_US/for-our-business-partners/energy-supply/electric-rfo/wholesale-electric-power-procurement/regional-solar-choice-program.page

BEST EXPLAINER ON CALI'S PROGRESS ON SHARED SOLAR:
https://www.greentechmedia.com/articles/read/a-rough-start-possible-reforms-for-californias-community-solar-program#gs.bOYl=6U


NREL 8-page PDF on community solar:
https://www.nrel.gov/docs/fy14osti/62367.pdf

this is NREL (i think) resource with map of states that have passed shared solar policy:
http://www.sharedrenewables.org/

Minnesota community solar local report
http://www.startribune.com/minnesota-s-solar-garden-program-takes-off-in-2017/464428133/

How to install solar panels:
https://us.sunpower.com/blog/how-many-solar-panels-do-you-need-panel-size-and-output-factors/

NREL solar pv technology basics:
https://www.nrel.gov/workingwithus/re-photovoltaics.html

NREL community solar basic explainer page:
https://www.nrel.gov/technical-assistance/community-solar.html


WOULD BE NICE: use time manager qgis plug in to do a geogiffy showing the lights coming on as time goes on and solar gardens are made (watch the solar gardens grow)
https://medium.com/@tjukanov/geogiffery-in-a-nutshell-introduction-to-qgis-time-manager-31bb79f2af19



QGIS/map details:

11-classwork is the Foundations file with the first shape files and waffle house csv we used when learning QGIS

US map projection:
NAD83 Conus Albers 

colors:
orange for dots: FF7F00
gray for map: E5E5E5; lighter one, per Maryanne rec: #f0f0f0
yellow highlight for MA, CO & MN: fff66a

FOR GEOGIFFY CONSISTENCY: graduated by Natural Breaks (Jenks); opacity at 50%; stroke hairline width with same orange color

-WHEN adding csv to QGIS, x field is the longitude and y field is the latitude


****SOMA'S PAGE WITH HELPFUL REMINDERS ON HOW TO USE QGIS:
https://gist.github.com/jsoma/0865246bd9223a6b86fe6876efb4c640

WaPo inspiration:
https://www.washingtonpost.com/graphics/national/power-plants/?utm_term=.0a9a89b4f867

2000, 2006, 2007, 2008: FF7F00 (my solar orange)
2009: blue #1f78b4
2010: 
2011:
2012:
2013:
2014:
2015:
2016:
2017:
2018:


TO MAKE MY ANIMATED SOLAR MAP:
1. Re-do csv files to have them include on year only
2. Create a map with each year's dots as a diff layer and make them each a diff, clearly distinct color (also lighten the gray, per MA's rec)
3. Export map as pdf from QGIS and open in Ai
4. Zoom out from map, select the artboard, open the artboard palette (from 'Window' dropdown) and select 'duplicate artboard'. Create a duplicate for each year we need.
5. Name each artboard after the year; make it same you want to name the png file that you'll eventually export.
6. Select by color and delete dots from maps as needed to make chronological. (Can lock artboards that you don't want to change if needed).
7. Make all the dots orange. 
8. File --> Export --> Export as... (MA uses this as opp to 'for the web') --> In save window that pops up, select 'Use artboards' near the bottom; this will create a png file for each artboard.
9. Google how to make an animated gif


-HOW TO EXPORT TO PNG OR SOMETHING USEABLE IN MARYANNE'S TEMPLATE WITH QGIS:
--> "New Print Layout" button (4th from the left on top of QGIS; it's in bet disk icon with green bit and the piece of paper with a wrench icon)
	--> give it a title in first small pop up box and click OK
		--> in big window that pops up, select area for the image by clicking the 'add a new map to the layout' button (it's a piece of paper with green +, 6th from the top); with tht selected, start at top left of 'artboard' like layout and drag to define area (I just did the whole thing or close to it); when you let go from the click and drag, the image you're trying to export should appear
			--> can use select (hand at top left) to manipulate the image as needed (zoom, move around, etc)
				--> from LAYOUT menu at the top dropdown, select 'Export as image'
					--> give it a name, navigate to where you want it, make sure it's type you want (png) and click save (ALL THIS WORKS SAME FOR PDF, WHICH IS REALLY WHAT YOU WANT SO CAN STYLE IN Ai)




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
