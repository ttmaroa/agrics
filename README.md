## INTRODUCTION

Fasten your seatbelt and lets take a trip down the Maji ndogo road(project). Here, we shall be looking at how different crops yield across 5 different provinces.

With matplotlib and seaborn being our tools of visualization. We'll create plots that show relationships between variables like rainfall, pH levels, and temperature.

Data used will be pulled from nearby weather stations for comparison with our farm measurements.

We'll use weather data from five stations across Maji Ndogo. Each field in our dataset is close to one of these stations, so we also have some data connecting each field in our dataset to the correct weather station. We're going to compare and validate key climate measurements



## Data dictionary

### 1. Geographic features

-Field_ID: A unique identifier for each field (BigInt).

-Elevation: The elevation of the field above sea level in metres (Float).

-Latitude: Geographical latitude of the field in degrees (Float).

-Longitude: Geographical longitude of the field in degrees (Float).

-Location: Province the field is in (Text).

-Slope: The slope of the land in the field (Float).

### 2. Weather features

-Field_ID: Corresponding field identifier (BigInt).

-Rainfall: Amount of rainfall in the area in mm (Float).

-Min_temperature_C: Average minimum temperature recorded in Celsius (Float).

-Max_temperature_C: Average maximum temperature recorded in Celsius (Float).

-Ave_temps: Average temperature in Celsius (Float).

### 3. Soil and crop features

-Field_ID: Corresponding field identifier (BigInt).

-Soil_fertility: A measure of soil fertility where 0 is infertile soil and 1 is very fertile soil (Float).

-Soil_type: Type of soil present in the field (Text).

-pH: pH level of the soil, which is a measure of how acidic/basic the soil is (Float).

### 4. Farm management features

-Field_ID: Corresponding field identifier (BigInt).

-Pollution_level: Level of pollution in the area where 0 is unpolluted and 1 is very polluted (Float).

-Plot_size: Size of the plot in the field (Ha) (Float).

-Chosen_crop: Type of crop chosen for cultivation (Text).

-Annual_yield: Annual yield from the field (Float). This is the total output of the field. The field size and type of crop will affect the annual yield.

-Standard_yield: Standardised yield expected from the field, normalised per crop (Float). This is independent of field size or crop type. Multiplying this number by the field size and average crop yield will give the Annual_yield.
