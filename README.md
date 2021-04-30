

### Flatiron Capstone Project, Analyzing  Energy Patterns and Environmental Impacts for power plants


## Overview

First we’ll be going over the introduction and Business problem. Aka outlining exactly what we are trying to do, what our expectations are, and why. We will then go over the data process to some degree, given that this presentation is non-technical we will be using broad strokes terms to underline the important processes, where they come from, and what we’ll be doing as far as cleaning and organizing our data is concerned.

After this we will be going over the results we were able to achieve with the data, what that means for our model and of course what it means for the governments of the countries we will be examining, and their citizens. Lastly, we’ll be going over what we still have to learn, aka what our model didn’t cover or what might be helpful from both a data science perspective and/or a humanitarian perspective. Energy and renewable energy especially, is always evolving, and so must our understanding of it as well as its’ applications.


## Business Problem(s)

The business problems we will be addressing and hopefully solving will be as follows: As your company begins expanding powerplants to different sectors and locations, finding both reliable and responsible energy sources is critical. Renewable energy is primarily sourced through naturally occurring phenomena, wind and solar energy are prime examples of this. Since the creation of these resources is beyond our control, for the time being, the best we can do is adapt our strategies to the natural patterns these phenomena hold towards. Some of these can be obvious, like solar panels won’t be very effective at night, but others can use some exploring. Which, will help us predict energy generation and allocate resources as necessary. We will also take a look at both traditional and on-traditional energy production and it’s environmental impact.

## Data and Methods

The data process is possible thanks to both open power systems data, a free to access database on renewable energy, and the National Aeronautics and Space Administration, which has kept detailed weather data for the past several decades.

The CO2 analysis we will be conducting is courtesy of data provided by the Environmental Information Administration, which encompasses different energy production sources and annual CO2 reading from the past few decades.

Comparing energy production, weather data, and carbon emissions all individually and separately, we took a look at any patterns present, what they could mean, and how we can use them to an advantage, which becomes much more feasible when comparing the different datasets across from each other. We will be comparing these datasets across one another to find any distinct advantages or disadvantages to specific energy sources, and an patters present that can help predict clean, renewable energy.



## Results and Conclusions

First thing we did was examine the historical output of each country across one year, the orange graph shows the solar energy production and the blue show the wind energy production. We used the Germany in 2018 as an example, since it was the most recent available for both production data AND weather data, which we will get into on the next slide. You can see that there are bumps in solar energy in the middle of the year, which is unsurprising since the onset of summer means more sunlight. Interestingly, Wind seems to behave in the opposite fashion, with a lull in production over summer months. This showcases the importance of having comprehensive and diverse energy plans, that will consistently produce year-round. We can see on the side of the charts that Germany has the highest overall production, no doubt due to their very progressive sustainable energy mandates. Interestingly though, you may be able to notice that Italy has a more consistent energy production across both wind and solar energy. This is most likely due to it’s coastal location. While Germany and France are by no means landlocked, Italy is a peninsula with lots of exposure to the Mediterranean. 


<img width="344" alt="Screen Shot 2021-04-23 at 4 52 11 AM" src="https://user-images.githubusercontent.com/72046733/116726237-dc882d80-a997-11eb-8a23-0ee50795356c.png">

<img width="338" alt="Screen Shot 2021-04-23 at 4 52 06 AM" src="https://user-images.githubusercontent.com/72046733/116726244-deea8780-a997-11eb-8fd6-16bb3ea1ff5a.png">

Both wind and solar energy production is aided due to its' proximity to the ocean, wind due to surface water's friction with the air, creating additional wind to power turbines, and solar due to the reflective properties of the ocean's surface, creating additional sunlight. Of course Italy is the southernmost of our three countries, and as such receives more sunlight year round.

Next we wanted to compare our weather data against production to see if we could find any reliable indicators of future production. Interestingly, Temperature was not the best indicator for solar energy production. Short wave radiation was far more accurate, and just as predictable. Wind energy was found not to correlate very strongly with any of the weather data we had on hand, though temperature was close enough to be worth mentioning. But since our goal is to reliably predict production based on weather patterns, simply being worth mentioning isn’t quite good enough.
After calculating the weather against the production for each country for one year, we were able to accurately determine the relationship between weather solar energy production for Germany, Italy, and France, with accuracy scores of over 93, 91, and 94% respectively, which is very high, and supports our initial idea of weather being correlated with energy production.

<img width="397" alt="Screen Shot 2021-04-23 at 4 53 14 AM" src="https://user-images.githubusercontent.com/72046733/116726222-d72ae300-a997-11eb-8e6e-0bb1c155feda.png">

The next portion of our analysis covered 9 different energy sources: Solar, wind, Oil, Coal, Dry and Liquid natural gas, Nuclear, Geothermal and Hydroelectric. Since we’re testing for these energy types and their relationship with carbon emissions, it makes sense to use the United States, the largest carbon producer in the world, to compare their relationships.
All 9 were analyzed from the beginning of the 21st century to 2019, and as you can see in the graph in the top right and probably also know off hand, CO2 has been rapidly increasing as our society advances.
Therefore, I thought the best course of action would be to test the production of each of our energy sources, and analyze it against the annual CO2 emission from the same timeframe to find which energy sources have the largest carbon footprints, and which we can rest a little easier while using. Unsurprisingly, Coal was the largest offender on the front, and wind had the lowest carbon impact.


<img width="557" alt="Screen Shot 2021-04-30 at 6 04 14 AM" src="https://user-images.githubusercontent.com/72046733/116726200-d1350200-a997-11eb-87e7-974f65ef5349.png">

Using the relationships we measured, we were able to predict rises in CO2 with an accuracy of 90% based on what we call the random forest method, which uses a series of yes no decisions to find the most favorable relationship.



## Future work

Based on these analyses, we have three concrete recommendations: First to use these predictions to divert energy, financing, and resources as needed, based on seasonality for renewable energy plants. Secondly, to expand Financing of Wind turbine energy, and find economic alternatives to coal. And Third to develop early warning systems for radiation, the earlier the data is available, the more time you will have to plan around it.

As far as future work goes there are certainly more than three suggestions, but I will keep it brief for all our sakes: There are of course more than two types of renewable energies, finding key predictors for each will be very advantageous, and looking beyond weather is highly recommended. Second to begin investigations on ideal locations by geography and energy type, for example where solar energy would be most productive and where hydroelectric might be most productive. Last would involve how to effectively phase out of fossil fuel energies, while minimizing the financial impact that would bring.


## For more information

Email: lfcaruccio@gmail.com
Github: luca-caruccio
Linkedin: Luca Caruccio

## Repository Structure

-Introduction and Overview

-Business Problems

-Data Methods

-Results

-Conclusions

-Future Work and Next Steps
