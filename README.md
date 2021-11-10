# Morris-portfolio
Telling Stories with Data Public Portfolio

# About me
My name is Deirdre (she/her) and I'm in the Public Policy and Management program here at Carnegie Mellon University. I'm from a small town in Maryland, but have lived in Pittsburgh the last three years. I've worked in law firms up until this shift in trajectory to public policy, so I am trying to make use of every learning opportunity that I come across while in the program. 

# What I hope to learn
Data visualization is incredibly powerful in this day and age, and a tool that is used (not always well) in just about every industry. The strategies and tools will all be new to me (I'm pretty impressed by it all right now). I hope to learn how to cater a visualization to a particular audience and how to create honest visualizations that are effective in communication. I plan to narrow this down but after I graduate, I am hoping to go into the policy analysis field. 

# Portfolio
Here's where my work for the class will go.

# Assignment 2
## Government debt bar chart (OECD Graphic)
OECD Graphic - Original
<iframe src="https://data.oecd.org/chart/6vvB" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6vvB" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2018</a></iframe>

## Grid of line charts (OECD Graphic)
A look at the Debt-to-GDP ratio across many parts of the World from 1995-2019
<div class="flourish-embed flourish-chart" data-src="visualisation/7696916"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## OECD Graphic - Personal Visualization
**A History of Debt to GDP Ratio across the World**

A country-customizable look at the Debt-to-GDP ratio from 1995-2019*

(*adjusted based on country-available data*) 
<div class="flourish-embed flourish-chart" data-src="visualisation/7698298"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


## Written Summary
All three visualizations are quite different in how they display the data. The first graphic (the bar chart) limited the data to a single year (2018) – which made the debt-GDP ratio values more digestible in connection with each individual country, though does not incorporate any time dimension. It also presented in order of lowest to highest debt to GDP ratio, which gave the reader a sense of scope. This was important in the sense that many readers might not know what ratio might be normal or common across the world. The order of this information also suggests most people might be drawn to the highest few countries, the lowest few countries, and perhaps 1 or 2 in the middle.

The following graphic (grid lines) introduces this data on a timeline and creates a graph for each country. If the intention is to compare countries, these individual graphs make that harder to do because of the eye travel required. It also meant that the y-axis for each small graph was quite compressed (to accommodate the large range), so most of the lines looked relatively the same - most ratios didn’t *appear* to have changed dramatically during the ’95-’19 time period. That said, once appreciating the values on the axis, this visualization did allow for a better understanding of how this ratio fluctuated over time in any one particular country. 
The last graphic of my choice (stacked area chart) continues with the idea that the countries should be displayed separately if maintaining the consideration of change over time. This third graphic is definitely catered to someone who would like to look at this time-based ratio for a specific country or just a few countries. The much larger space dedicated to each country meant a greater opportunity to appreciate the actual ratios that were associated with each year for a given country. But, given the greater space for detail meant less opportunity to find general patterns across the dataset.

Why I chose this visualization: After quite a bit of experimentation, I chose the third data visualization because every visualization that included all 3 variables (countries, timeline and ratios) together seemed too crowded to discern what data connected with what country. I did really like the possibility of using a bar chart race - have the graphic adjust the ratios as the chart moves through the years, but I needed the raw data to be displayed with years as the column headers (rather than vertically) and I assumed the intention was probably to stick with the data as-is. Using the stacked area chart with a row filter on the country as I did, is catered to a reader who might want to view this ratio over time for a particular country or a handful of countries, easily toggling between a few via the dropdown. The default template adjusted both the x and y-axis based on the available data and relevant range, respectively. I found it important to set those parameters (setting the x-axis min 1995 - max 2019 and y-axis min 0 - max 260) so that the data didn't appear manipulated and you could meaningfully compare different countries without taking into consideration different scales. I chose the dark pink color scheme to communicate that this value can be concerning as it gets higher (but a red would have been overkill, I think). I can appreciate that all three visualizations highlight different information and make the decision to prioritize some data over others.

# Assignment 3/4 #
## Original data visualization ##
![image](https://user-images.githubusercontent.com/92800996/141031134-cd582bb1-cb13-4a65-ad7b-6933feba450e.png)
Soure: BP (https://www.bp.com/en/global/corporate/energy-economics/statistical-review-of-world-energy/oil.html)

I selected this particular data visualization because I am interested in energy broadly and BP had a number of interesting visualizations (and reams of available data). As expected, I ended up 'informally' critiqueing quite a few of BP's visualizations - on renewables consumption, electricity generation, etc. Most of their visualizations were quite good and appropriate within their contexts. In the process, I appreciated how easy it can be to find how a visualization fails in some measure or another, but much more difficult to actually design something better. Part of the reason I chose this visualization was because I had an idea of how I would redesign it.   

As an extension of that what I've mentioned above, the critique method grounded my review in how to prioritize in the redesign. Being new to data visualization has meant an initial gravitation towards something more "fancy", when in actuality clarity, completeness, usability, etc. are all far, far more important.  When considering the "truthfulness" factor, I knew I wanted to provide some sort of clarifying highlight on the different population densities of the regions.  
 
Moving to the wireframe, I wasn't quite sure how I'd move to the draft version of my idea. I played around in Basalmiq a bit (without much luck in drafting what I had in mind) and considered what it might look like on paper - maybe yearly graph skteches with arrows in between showing progression? It turns out (and after seeking the advice of the Professor), wireframing within the tool I planned to use for the final redesign (Flourish), was a much more effective platform based on what I wanted to do. From there, I got very relevant and specific feedback that I could incorporate directly. Unintentionally, I ended up getting the feedback in stages (based on when people could get back to me) - and I was editing the visualization in real time (I've included the first iteration in the link above). As such, I was able to adjust oversights (small in nature, but largely impacting the completeness of the visualization) ahead of the next feedback and receive more substantive comments each time. The most prominent example of this was that initially, I had no units!

Below are a compilation of the answers I received to the following questions:

- Can you tell me what you think this is?
Luckily, no one had much of an issue identifying what they thought the visualization was - most answered something like "a graph of oil consumption over time by region"

- Can you describe to me what this is telling you?
The answers to this did vary a bit - some literal: a "dynamic representation of oil consumption by geographic region throughout the years. It displays the 'rank' of a region based on oil consumption throughout the years of the data"; some more analytical: "consumption pattern has shifted from North America and Europe to Asia-Pacific in the last 30 years". Additionally, it was encouraging that others still picked up on the decrease in oil consumption in some regions in recent years - a trend that I thought was maybe less obvious in my redesign.

- Is there anything you find surprising or confusing?
Some were surprised that North America didn't dominate this visual more than it already does. Others were surprised by the dramatic rise in consumption in the Asia Pacific. One or two were curious what the running total exactly meant. And just about everyone was confused what CIS stood for until I changed it!

- Who do you think is the intended audience for this?
Most thought the graphic was intended for an energy policy or oil industry audience, while others thought it appropriate for the general public (with an interest in energy or natural resources). Importantly, a lot of folks wanted to learn more! Why did oil consumption decrease as depicted? 

- Is there anything you would change or do differently?
There were a few tweaks mentioned here - either small clarifying things (units, labeling and margins, etc.) or larger conceptual things (misleading Asia Pacific region based on population). During the class exercise, I was also encouraged to tell a more compelling story with the data (more on that below!). 

Most of the constructive feedback I got, I incorporated - the most significant being the note I added regarding Asia Pacific's population. Even though I knew I wanted this myself during my initial critique, it really took some time to consider how best to clarify this information. I experimented rethinking the design altogether and moving to a bubble chart to make population density they key component of the graphic. However, after some trial and error, I resorted back to the original intention (to show oil consumption by region, over the last 25 years) with a clear, clarifying caption. I also made various tweaks to the layout based on what I've learned about white space and more general best practices. Some of the feedback also indirectly helped me narrow down what was important to show: do I need the running total? Is that adding to the story? I thought that it was but then decided it was taking away from the main regional data.

All that said, my redesigned visualization shows how daily oil consumption has fluctuated in the last 25 years and no more so than in the Asia Pacific. The chosen caption is intended to highlight that the Asia Pacific includes the two most populous countries in the World and should be interpreted accordingly. That was the most important thing that I changed from the initial visualization. It was also important to me to show these regional consumption amounts on a scale that highlighted how stark the differences really were. In a moment where wealthier countries are being asked to help developing nations prepare for the impacts of climate change (e.g. African coastal cities) a visualization like this - African oil consumption pales in comparison with North American consumpion - puts that into perspective. 

<div class="flourish-embed flourish-bar-chart-race" data-src="visualisation/7759980"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
