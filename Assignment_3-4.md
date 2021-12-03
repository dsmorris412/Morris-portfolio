# Assignment 3 & 4 #

## Original data visualization ##
![image](https://user-images.githubusercontent.com/92800996/141031134-cd582bb1-cb13-4a65-ad7b-6933feba450e.png)

Source: [BP](https://www.bp.com/en/global/corporate/energy-economics/statistical-review-of-world-energy/oil.html)

## Critique the Data Visualization ##

I selected this particular data visualization because I am interested in energy broadly and BP had a number of interesting visualizations (and reams of available data). As expected, I ended up 'informally' critiqueing quite a few of BP's visualizations - on renewables consumption, electricity generation, etc. Most of their visualizations were quite good and appropriate within their contexts. In the process, I appreciated how easy it can be to find how a visualization fails in some measure or another, but much more difficult to actually design something better. Part of the reason I chose this visualization was because I had an idea of how I would redesign it.   

The critique method grounded my review in how to prioritize the redesign. Being new to data visualization has meant an initial gravitation towards something more "fancy", when in actuality clarity, completeness, usability, etc. are all far, far more important.  When considering the "truthfulness" factor, I knew I wanted to provide some sort of clarifying highlight on the different population densities of the regions.  
 
Moving to the wireframe, I wasn't quite sure how I'd move to the draft version of my idea. I played around in Basalmiq a bit (without much luck in drafting what I had in mind) and considered what it might look like on paper - maybe yearly graph skteches with arrows in between showing progression? It turns out (and after seeking the advice of the Professor), wireframing within the tool I planned to use for the final redesign (Flourish), was a much more effective platform based on what I wanted to do. From there, I got very relevant and specific feedback that I could incorporate directly. Unintentionally, I ended up getting the feedback in stages (based on when people could get back to me) - and I was editing the visualization in real time (I've included the first iteration in the link above). As such, I was able to adjust oversights (small in nature, but largely impacting the completeness of the visualization) ahead of the next feedback and receive more substantive comments each time. The most prominent example of this was that initially, I had no units!

## Wireframe & Test the Solution ## 

Wireframe link [here](https://public.flourish.studio/visualisation/7781419/)

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

## Build the Solution ## 

### Daily Oil Consumption by Region (in millions of barrels) ###
<div class="flourish-embed flourish-bar-chart-race" data-src="visualisation/7759980"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
