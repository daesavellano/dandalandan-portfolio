---
title: "NBA Play-by-Play Analysis"
featured_image: ../assets/images/featured/TSWD_Basketball.png
summary: Analyzed 2017-2019 Golden State Warriors play-by-play data to measure star players' impact on team performance. This dashboard visualizes on/off metrics for stars like Curry, Durant, and Thompson.
date: 2025-11-04
draft: false
type: "page"
---

### Applying TSWD insights outside the classroom

- **Goal:** To analyze 2017-2019 Golden State Warriors play-by-play data to answer the question: *"Do star players make their teammates better?"*
- **Key Finding:** In GSW, star presence significantly boosts a lineup's **overall** offensive efficiency, but not necessarily their teammates’ **individual** efficiency. This is primarily because GSW's star-heavy lineups created a "star overlap" problem, where even "off-court" scenarios still featured elite talent.
- **Process & Tool Rationale:** While this was an assignment for my `Advanced AI and Enterprise Strategy` class, I used it as an opportunity to apply principles from `Telling Stories with Data`. Although the assignment did not specify Tableau, I intentionally selected it over a programmatic approach like Python.
    
    As I had limited domain knowledge in basketball, Tableau's visual interface was a significant asset. It enabled a more exploratory process, making it possible to discover the 'star overlap' narrative—the key insight needed to explain the finding. Furthermore, using Tableau made it much easier to filter and analyze the large NBA play-by-play dataset. This project affirmed the value of visual tools for independent data exploration and storytelling, moving beyond guided exercises.

As you explore the dashboard below, feel free to interact with the table sorting and dropdown functionality. Additional information can also be obtained by hovering over the visualizations.

<div class='tableauPlaceholder' id='viz1762291263126' style='position: relative'><noscript><a href='#'><img alt='All Info ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;NB&#47;NBAPlay-by-PlayAnalysisStarPlayersasTeammates&#47;AllInfo&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='NBAPlay-by-PlayAnalysisStarPlayersasTeammates&#47;AllInfo' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;NB&#47;NBAPlay-by-PlayAnalysisStarPlayersasTeammates&#47;AllInfo&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1762291263126');
    var vizElement = divElement.getElementsByTagName('object')[0];
    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='850px';vizElement.style.height='1227px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='850px';vizElement.style.height='1227px';} else { vizElement.style.width='100%';vizElement.style.height='1727px';}
     var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


**References & Acknowledgements**

**Data Source:** The data was provided to us as part of our assignment, but is likely available online if you look up "NBA Play-by-Play Data." If I find it, I will ensure I add it here!

**AI Acknowledgement:** Google Gemini was used to better understand basketball terminology.