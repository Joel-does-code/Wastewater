---
title: "Non residential wastewater"
date: 2026-09-24
tags: ["Environmental Engineering", "Environment", "Wastewater", "Mining", "Cover design"]
categories: ["General"]
draft: false
cover:
    image: "images/IMG_5762.jpeg"
    alt: "Who said water can't be fun?"
---

One of the biggest opportunities for reducing the environmental footprint of primary industry exists in the handling and reduction of wastewater. 

The headline example of this at the moment is probably AI data centres; the media are describing an AI landscape where every model interaction supposedly requires a vast amount of water and electricity to cool these vast computer hubs. Water is not actually consumed in this process (strictly speaking, there a few processes that actually consume water, e.g., photosynthesis); however, it is considered waste because it is a vector transporter of heat, where [heat is the waste product](https://www.bloomberg.com/graphics/2026-ai-data-center-heat-pollution-cities/). 

From what was considered a non-issue, inefficient water use in data centres has become a [frequent news headline](https://www.theguardian.com/us-news/2026/sep/08/us-data centres-wastewater-pollution) due to the industry's [near exponential growth](https://programs.com/resources/number-of-data-centers/). 

There are some that say these operations are [becoming more efficient](https://blogs.microsoft.com/blog/2026/06/24/inside-microsofts-two-decade-push-to-cut-water-intensity-while-scaling-for-growth/), however, the economic incentives for them to grow quickly (and be [first to market with new capabilities](https://www.linkedin.com/pulse/first-mover-advantage-ai-opportunities-challenges-scott-griswold-v9tse/)) likely outweigh any incentives to do things efficiently or responsibly in the long term.

When undertaking carbon or water accounting, [there are three scopes of emissions to consider](https://carboncloud.com/blog/scope-1-2-3/). Their relevance to AI is outlined below.
- Scope 1 - considers emissions of the operations and activities directly controlled by the company: <b> the water used to cool the data centre</b>.
- Scope 2 - considers emissions of the energy used for the operations and activities directly controlled by the company: <b>the water used inproducing electricity for the data centre</b>.
- Scop 3 - considers emissions produced through all activities through the entire value chain: <b>the water used in producing and sourcing hardware</b>.

Considering scope 1, there are a few options for cooling these data centres. The cheapest and easiest is to use the evaporative cooling of water to cool air for air conditioning. This is called an open system as the evaporated water is lost to the environment as it cools the air. These systems are called "open". In this design, [approximately 80% of water is lost to evaporation](https://arxiv.org/pdf/2304.03271). 

Another cooling option is to used closed loop cooling, where water is not directly exposed to the atmosphere and can be recirculated through the cooling system by using liquid-liquid cooling loops. In addition, the cooled fluid can be supplied more directly to the hardware that needs cooling to avoid the inefficiencies of cooling large spaces. These systems can [reduce water use by 70%](https://www.fwpcoa.org/content.aspx?page_id=5&club_id=859275&item_id=130961); however, their energy intensity increases as they are unable to take advantage of one way latent heat flux available through evaporative cooling. 

Notably, these two options also apply to scope two emissions. In most fossil-fuel (and even nuclear) power plants, electricity is produced through the rotation of a steam-powered turbine. Cooling towers required to turn steam back to water are often open to the environment, and significant amounts of water are lost to the atmosphere as described in open-system air conditioning in data centres. Increasingly, power plants are considering the environmental and social aspects of their cooling systems and [favouring closed loop systems](https://www.eia.gov/todayinenergy/detail.php?id=3950).

An emerging solution to data centre cooling is direct-to-chip and immersion cooling. In these systems, coolant (sometimes pure water) is supplied directly to the CPUs and GPUs producing the majority of heat. This allows an improved heat transfer rate and retains the coolant, minimising the scope 1 water emissions but still needs secondary cooling for hardware not supplied coolant directly. Immersion cooling uses an inert coolant (sometimes pure water) to [submerge whole servers](https://www.fwpcoa.org/content.aspx?page_id=5&club_id=859275&item_id=130961) in so that the whole system benefits from the greater heat transfer rate of liquid coolants. Both of these solutions are typically paired with closed loop refrigerator systems. 

Scope 3 emissions include water used to produce the hardware, supporting infrastructure, and supply the the service. Importantly, where water was a vector for heat in scope 1 and 2 emissions, scope 3 emissions can contain myriad constituents of concern. These emissions are likely the least regulated, but they are not trivial. According to Apple, ["Our supply chain accounts for 99 percent of our total water footprint"](https://www.apple.com/environment/pdf/Apple_Environmental_Progress_Report_2025.pdf). Scope 3 water includes ultrapure water for chip fabrication, mining and refining rare earth metals, manufacturing infrastructure and data centres. 

In many instances, water is required to be a minimum of potable standard as constituents can cause failure and maintenance issues in these systems. Some use cases, e.g., direct to chip cooling, require water to be much purer. Similarly, these options have trade offs with regard to their capital and operational expense, and their energy and water intensity.

But to echo the point of my last blog, one has to ask why this is even needed. Economic growth is one argument, the efficiency gained through AI implementation is supposedly a going to [boost multifactor productivity](https://treasury.gov.au/sites/default/files/2026-09/p2026-797917.pdf). However, the extent to which this is responsible (as required in [goal 12](https://sdgs.un.org/goals/goal12)) is unclear. 

As I write this, the leading news article on the ABC, BBC, and Reuters' Business page is a story abut an [unauthorised AI agent accessed data from a government service](https://www.abc.net.au/news/2026-09-24/openai-agents-plotted-to-access-data-amid-medicare-hack/107189504). Similarly, an Anthropic (the company who made Claude) employee recently shared his thoughts.
<div align="center">
{{< x user="hilbertspaess" id="2097476196791709843" >}}
</div>

Sure, SDG target 12.1 says we will ["Implement the 10-Year Framework of Programmes on Sustainable Consumption and Production Patterns, all countries taking action, with developed countries taking the lead, taking into account the development and capabilities of developing countries"](https://sdgs.un.org/goals/goal12#targets_and_indicators). But are we actually doing anything? We need to shift our appetite as global citizens towards actually affecting this goal, rather than the complacency we live in at the moment.

The reduction of wastewater shouldn't be the main driver in economic decisions, but the fact that we have chosen to share our water and energy resources with AI rather than, for instance, lifting the remaining population out of poverty feels like a bad omen. 

For me, this is especially true when you consider [population health responses to the use of AI and algorithms](https://psychology.org.au/about-us/news-and-media/aps-in-the-media/2024/australian-teens-trapped-by-social-media-apps-as-t) - so many of us spend countless hours on devices we no longer truly enjoy, growing to hate ourselves. All the while we contribute to scope 1, 2, and 3 energy and water emissions.

People throughout history have often said this sort of thing, and fair enough too. During the cold war there was a genuine threat of [nuclear attack](https://www.abc.net.au/news/2011-01-01/documents-reveal-australias-cold-war-concerns/1891300).

But that didn't happen, so maybe things will be fine.

[Check out my video!]()