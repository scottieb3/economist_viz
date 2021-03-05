# Data visualization projects 
(that I'm allowed to share)


## Mining Presidential debates to understand interactions

`2016 all debates.png` and `2016 rep debate 02.png` are two network visualizations of how candidates interacted with each other in the debate.  Edges are weighted by how often candidate A spoke _immediately_ after candidate B.  

No prize for correctly guessing who took every opportunity to add himself to the conversation.

Data programmatically scraped from UCSB's Presidential debate archive in early 2017.  Scraping done using **python** / **beautifulsoup**, analysis done using python / **pandas** and **R** / **qgraph**.


## Run Every Street
I've joined the small group of oddballs embarking on an absurd completionist quest: run every string stretch of paved road in our hometowns.  (Search #runeverystreet on Instagram to see it's not a unique obsession).

`Scott_2020_SF.gif` is my summary of this year of lockdown where (almost) all runs started and ended at home for me.

Data pulled from Strava's API and images created using Mapbox's new (and confusing) Tileset API.  

Generate your own @ [runprogress.com](https://www.runprogress.com/) !  App powered by python / (**flask** + **requests**)


## Visualize order flow
At Snapdocs, mortgage transactions had to be processed in a work queue to prepare for signings.  For fun and to quickly show bottlenecks, I visualized the non-linear workflow of the previous day using d3.

Sample data only shown in `sample_workflow_d3.html`

Production version uses a **Redshift database** (refreshed on schedule by Mode Analytics SQL notebook) to push data to **d3**.


## Shut up already Scott
One of the keys in combating systemic bias in the workplace is to enforce more equitable participation in decision-making meetings.  In an attempt to be more aware of blabbermouths (like me), I started recording our Zoom meetings to collect data on talk times.

`timesnips_prioritization.png` and `timesnips_demo.png`  show two separate meetings of various equality.

Data pulled via Zoom using python / pandas and visualized using python / **plotly express**.


## Quick data nuggets
As part of a sporadic blog posting, I investigated the relationship of pay and employee retention (`company names.png`) and the efficacy of different strategies in a multi-arm bandit scenario (`efficiency single run.png`).

Both were explorations in finding more interprable ways to display complex data. 

Read more @ https://medium.com/@scott_in_2d
