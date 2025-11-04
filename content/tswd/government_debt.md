---
title: "Debt-to-GDP Ratios"
featured_image: ../assets/images/featured/TSWD_BeyondtheBox.png
summary: Analyzed the government debt-to-GDP ratios of 34 OECD countries from 1995 to 2019. Two sample visualizations are included—a heatmap and a combined box plot and line chart. The final design focuses on Japan as an outlier.
date: 2025-11-03
draft: false
type: "page"
---

For this assignment, I analyzed the government debt-to-GDP ratios of 34 OECD countries from 1995 to 2019. My analysis began with the tutorial's heatmap, which visualized these ratios across all countries and years. This initial view was effective for a broad overview and immediately highlighted a key anomaly: Japan’s 239:1 debt-to-GDP ratio. This significant outlier in a famously stable economy intrigued me. I explored the full distribution over time, which confirmed Japan as a consistent, and *growing*, outlier. I found a compelling story in this data, which I chose to visualize in three phases: an initial divergence point, the impact of the 2008 financial crisis, and recent signs of a plateau.

<div class='tableauPlaceholder' id='viz1762230754191' style='position: relative'><noscript><a href='#'><img alt='Debt-to-GDP ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebt-to-GDPRatios1995to2019&#47;Debt-to-GDP&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GovernmentDebt-to-GDPRatios1995to2019&#47;Debt-to-GDP' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebt-to-GDPRatios1995to2019&#47;Debt-to-GDP&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1762230754191');
    var vizElement = divElement.getElementsByTagName('object')[0];
    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='850px';vizElement.style.height='527px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='850px';vizElement.style.height='527px';} else { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*1.77)+'px';}
     var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

While the heatmap was useful for *spotting* this outlier, I felt it was less effective at telling the story of that outlier's relationship to the rest of the distribution over time. The heatmap flattens the data, making it hard to compare one country's trajectory to the group's central tendency. My goal was to create a visualization that put the narrative of Japan’s divergence front and center. To achieve this, I chose a combination of boxplots and a line chart as my redesigned chart type. This was a materially different and, for my specific narrative, more effective choice. The boxplots' primary strength here is its ability to show the full distribution of the other 33 countries (their median, interquartile range, and whiskers) for each year, while simultaneously plotting Japan as a distinct point far outside that range. This direct visual comparison is the core of the story.

<div class='tableauPlaceholder' id='viz1762230777687' style='position: relative'><noscript><a href='#'><img alt='Japan vs All ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Be&#47;BeyondtheBoxJapansDebt-to-GDPRatioasaGlobalOutlier&#47;JapanvsAll&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='BeyondtheBoxJapansDebt-to-GDPRatioasaGlobalOutlier&#47;JapanvsAll' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Be&#47;BeyondtheBoxJapansDebt-to-GDPRatioasaGlobalOutlier&#47;JapanvsAll&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1762230777687');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width='850px';vizElement.style.height='527px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

To enhance this narrative, I made several specific design choices. First, unlike the original scrolling heatmap, I designed this chart to be visible in one static view. While this resulted in thinner boxplots, I found it was a worthwhile trade-off to effectively display the entire timeline being studied.

I customized the color scale to serve the message. I used a muted, neutral gray color for the boxplots themselves, allowing the group's distribution to serve as context without drawing focus. In contrast, I plotted Japan as bright red dots, a specific choice to evoke the shade used on the Japanese flag. To ensure that no other points would be distracting, I created a calculated field that isolated Japan's data, rendering all other outlier points white to blend into the background (effectively hiding them). This follows the design principle of using color strategically to guide the user's eye, immediately highlighting the primary subject of the visualization.

To emphasize the trend, I used a dual axis to connect Japan's dots with a line, clearly communicating its trajectory over time. I decided to use a lighter color for this connecting line so that the emphasis would remain on the red dots. I also added annotations for the three phases I identified, included custom tooltips for on-hover context, and ensured that the OECD data source was clearly cited on the dashboard. I titled the figure “Beyond the Box: Japan’s Debt-to-GDP Ratio as a Global Outlier”—a title that is both a catchy hook and a literal description of Japan’s data appearing far "beyond the box."

**References & Acknowledgements**

Organisation for Economic Co-operation and Development (n.d.). *General government debt.* https://www.oecd.org/en/data/indicators/general-government-debt.html.

**AI Acknowledgement:** Google Gemini was used to help generate catchy titles and debate design decisions (i.e., connecting the outlier dots, adding color to the boxplots).