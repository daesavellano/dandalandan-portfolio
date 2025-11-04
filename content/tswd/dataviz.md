---
title: "Data Visualization Examples"
featured_image: ../assets/images/featured/TSWD_Datawrapper.png
date: 2025-10-30
draft: false
type: "page"
---

# Data visualization examples
This page contains example data visualizations from the Telling Stories With Data course, along with appropriate citations, references, and data sources used.

- [Government Debt-to-GDP Ratios](#government-debt-to-gdp-ratios)
- [Learning Tableau and Datawrapper](#learning-tableau-and-datawrapper)
    - Tableau: [Trust in Media](#trust-in-media)
    - Datawrapper: [Popularity of Visualization Types](#popularity-of-datawrapper-visualization-types)

## Government Debt-to-GDP Ratios

*Full writeup available in [Debt-to-GDP Ratios](../government_debt/) page.*

In this assignment, I analyzed the government debt-to-GDP ratios of 34 OECD countries from 1995 to 2019. My analysis began with a heatmap that visualized these ratios across all countries and years. This initial view immediately highlighted Japan's 239:1 debt-to-GDP ratio, a striking outlier. Intrigued by this anomaly in a stable economy, I explored the full distribution over time. This confirmed Japan as a consistent outlier, a story I chose to tell in three phases: divergence, a 2008 financial crisis, and signs of a plateau.

<div class='tableauPlaceholder' id='viz1762230754191' style='position: relative'><noscript><a href='#'><img alt='Debt-to-GDP ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebt-to-GDPRatios1995to2019&#47;Debt-to-GDP&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GovernmentDebt-to-GDPRatios1995to2019&#47;Debt-to-GDP' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebt-to-GDPRatios1995to2019&#47;Debt-to-GDP&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1762230754191');
    var vizElement = divElement.getElementsByTagName('object')[0];
    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='850px';vizElement.style.height='527px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='850px';vizElement.style.height='527px';} else { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*1.77)+'px';}
     var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

While the heatmap was useful for spotting this outlier, I thought that the narrative of Japan's divergence from the overall distribution could be put in the forefront. This story was perfectly captured by a boxplot, which highlights Japan as a global outlier while showing the full distribution. I also annotated the boxplots with the three phases I mentioned above, included custom tooltips for on-hover context, and added a trend line so that Japan's trajectory over the years can be on display.

<div class='tableauPlaceholder' id='viz1762187270914' style='position: relative'><noscript><a href='#'><img alt='Japan vs All ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Br&#47;BreakingtheCeiling&#47;JapanvsAll&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='BreakingtheCeiling&#47;JapanvsAll' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Br&#47;BreakingtheCeiling&#47;JapanvsAll&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1762187270914');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width='850px';vizElement.style.height='477px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

## Learning Tableau and Datawrapper

### Trust in Media

This Tableau dashboard was created as a reintroduction to the tool. It explores American trust in major news organizations across two different years.
- The **top graph** visualizes which news organizations Americans trusted most in **2018**, based on data from [Simmons Research](https://infogram.com/276787a2-ff55-457f-9a29-c0a8267b8b29).
- The **bottom graph** shows the **2024** net trust rating (the percentage point difference between "trust" and "distrust") for various outlets, using data from and based on an existing visualization in [YouGov](https://today.yougov.com/politics/articles/49552-trust-in-media-2024-which-news-outlets-americans-trust).

<div class='tableauPlaceholder' id='viz1761885112194' style='position: relative'><noscript><a href='#'><img alt='Trust in News (2018 and 2024) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Tr&#47;TrustInMedia_17618797080800&#47;TrustinNews2018and2024&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TrustInMedia_17618797080800&#47;TrustinNews2018and2024' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Tr&#47;TrustInMedia_17618797080800&#47;TrustinNews2018and2024&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1761885112194');
    var vizElement = divElement.getElementsByTagName('object')[0];
    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='850px';vizElement.style.height='1127px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='850px';vizElement.style.height='1127px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}
     var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

### Popularity of Datawrapper Visualization Types

The following graph was made as an introduction to [Datawrapper](https://datawrapper.dwcdn.net/Tb9rk/2/).

For this in-class exercise, we were given the data with no instructions other than to explore the website. With the limited time, I decided to implement the following design choices.
- I used a **bump chart with curved lines**, as it's a highly effective way to visualize how rankings change over time.
- I framed the data as a **"battle" between tables and area/line charts**, inspired by Datawrapper's common use in journalism (and need for catchy titles!). The color scheme also highlights this narrative: the current "winner" is green, the previous winner is orange, and all other chart types are grey.
- I chose a **horizontal format**, as it aligns with how Western audiences read time-based data (left to right), reinforcing the clear progression.

<iframe title="How The Tables Have Turned" aria-label="Line chart" id="datawrapper-chart-Tb9rk" src="https://datawrapper.dwcdn.net/Tb9rk/2/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="437" data-external="1"></iframe><script type="text/javascript">window.addEventListener("message",function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r,i=0;r=e[i];i++)if(r.contentWindow===a.source){var d=a.data["datawrapper-height"][t]+"px";r.style.height=d}}});</script>