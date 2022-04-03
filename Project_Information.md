Background

The North Brae gas condensate field is located in Block 16/07a and comprises both the North Brae Main channel and the Bracken channel. North Brae was discovered in 1975 with discovery well 16/07-1. The North Brae field has been developed via the Brae Bravo platform. Production by gas recycling started in April 1988. Gas sales commenced in 1995 and reinjection of dry gas ceased in 1999.The North Brae field can be subdivided into two major compartments, the Main Channel area and the Bracken area. The Main Channel area is volumetrically larger (90% GIIP), covering the southern two thirds of the field. Hydrocarbons within this part of the field are gas condensate. Production of gas and liquids commenced from well B1 in April 1988 at a rate which peaked at 95 MMscf/d. Development drilling continued and the field reached a plateau rate of approximately 550 MMscf/d at the end of 1991. Gas injection commenced in well B2 in May 1988 and, after removal of liquids, all dry sour gas was reinjected into the reservoir until gas export via the SAGE pipeline system commenced in 1995. Gas injection was reduced steadily until late 1999, when it essentially ceased. Gas production came off plateau in 1995 and has declined to 20 MMscf/d by 2009 as the pressure has depleted and wells have progressively watered out due to water influx from the north east. 
The dataset provided to you contains some information regarding North Brae wells. The following is the list of information and corresponding units.

Data	Units
Dry_Oil_Vol	Sm3
Gas_Vol	kSm3
Water_Vol	Sm3
Choke_Size_Prod	%
Fline_Press	barg
Fline_Temp	C
Flowing_THP_Prod	barg
Shut_in_THP	barg

The following could be done to analyse dataset. 

1.	Data consistency review.
a.	Plot choke setting against gas, oil and water production. What do you observe?
b.	Plot WHT, fline with production data.
c.	Correlation could be done with each well with total gas production.
d.	Plot water production for each well.
2.	Plot cumulative gas production for each well. Which wells production the most gas? 
3.	Plot condensate gas ratio for each well. What do you observe?
4.	Plot WGR. Explain how water progressed through field life.
5.	Understand the how fline pressure changes with time. Plot the data points when the field(all the wells) were shut in.
6.	Calculate reservoir pressure from Fline assuming the well is only gas filled. 
7.	Extract map of North Brae and well locations. https://data-ogauthority.opendata.arcgis.com/pages/e-a-wells.
a.	Could you create a normalised bubble plot for gas oil and water production and identify most prolific areas of the fields.
8.	Can you forecast how much gas left in each well? You could fit exponential decline through well production and forecast it.




Calculating Reservoir Pressure: 

Reservoir pressure could be calculated from fline(CITHP/Shut in THP). When the all the wells are shut in the reservoir pressure can be calculated. By measuring closed in tubing head pressure when all the wells are closed reservoir pressure can be calculated. For this to happen we need to make some assumptions around tubing content. The key assumption will be that the tubing is gas filled. Depth of each well will be available in https://data-ogauthority.opendata.arcgis.com/pages/e-a-wells. You need to look for North Brae Field and identify wells and reservoir depth. The following formula is for calculating reservoir pressure Pr:

Pr=P(CITHP)+gas gradient*depth. 

Assume gas gradient is 0.1 psia/ft. 

Depth should be true vertical depth from wellhead to reservoir. 


Acronyms:

CGR: The ratio of the volume of liquid oil produced to the volume of gas produced. Units in bbl/mmscf. 

1 m3 of liquid = 6.29 bbl
1 sm3 of gas = 35.31 scf

WGR: The ratio of the volume of water produced to the volume of gas produced. Units in bbl/mmscf. 

CITHP: Closed in tubing head pressure. 

GIIP: Gas Initially In Place





