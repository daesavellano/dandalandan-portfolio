---
title: "Critique by Design"
featured_image: ../assets/images/featured/TSWD_Evictions_Draft_2.png
date: 2025-11-08
draft: false
type: "page"
tags: "Template"
---

<center>
    <h1>Monthly Eviction Filings in America</h1>
    <p>The "Critique by Design" assignment was a very iterative process. You can find my full process below or skip directly to step 5 where I built the final visualization.</p>
</center>

- [Step One: The Original Visualization](#step-one-the-original-visualization)
    - Notes about the visualization and the organization
    - Why I selected this topic
- [Step Two: The Critique](#step-two-the-critique)
    - Data Visualization Effectiveness Profile
    - Audience & Effectiveness
    - Overall Observations
    - Redesign Focus & Next Steps
- [Step Three: Sketch and Iterate a Solution](#step-three-sketch-and-iterate-a-solution)
    - Draft 2 Feedback and Changes
    - Draft 3 (Pre-Class Feedback Version)
- [Step Four: Test the Solution](#step-four-test-the-solution)
    - Interview Questions
    - Draft 3 Feedback and Changes
- [Step Five: Build the Solution](#step-five-build-the-solution) *— Click here to skip ahead and see the final visualization.*
    - Summary
    - Main Changes
    - About the Process

## Step One: The Original Visualization

For this redesign, I am primarily looking at the landing page and the first graph you can see when you scroll on the [Eviction Tracking System](https://evictionlab.org/eviction-tracking/) by [The Eviction Lab](https://evictionlab.org/about/) at Princeton University. This is based on data from the [2023/W38 Makeover Monday challenge](https://data.world/makeovermonday/2023w38).

- The visualization is the first thing a user sees on the tracking page, featuring a map of the United States and large summary statistics.
- The second visualization can be seen after scrolling to the next page.
- Beyond the screenshot, there are additional visualizations that can be revealed by scrolling to the “filings by location" section.

<center><a href="https://evictionlab.org/eviction-tracking/"><img src="/images/posts/tswd/critique_by_design/Eviction_Lab_2025.png" alt="2025 Eviction Lab Screenshot" style="max-width: 70%; height: auto;" /></a></center>

### Why I chose this visualization
- **As a designer and storyteller,** I thought that redesigning this visualization would be a fun challenge. I added the constraints of matching the organization’s branding. It was already a lovely baseline, and my goal is not to top it. Instead, my main goal is to make it more consolidated and add a story layer.
- **As an aspiring health policy analyst,** the topic of eviction is very important, and the dataset I was able to get from Makeover Monday only had data from 2020-2023, with the baseline being pre-pandemic levels.

## Step Two: The Critique

### Data Visualization Effectiveness Profile

For my critique, I scored the visualization based on various informative and emotive criteria from Stephen Few's [Data Visualization Effectiveness Profile](http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf). A summary of the results, along with comments when you hover over each circle, can be found below.

<div class='tableauPlaceholder' id='viz1762600971634' style='position: relative'><noscript><a href='#'><img alt='Critique by Design ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ev&#47;EvictionsintheUSA-Critique&#47;CritiquebyDesign&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='EvictionsintheUSA-Critique&#47;CritiquebyDesign' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ev&#47;EvictionsintheUSA-Critique&#47;CritiquebyDesign&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1762600971634');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width='850px';vizElement.style.height='257px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

The effectiveness profile was very helpful in pinpointing the areas where I could improve the original visualization. It felt like an inspection report, and I appreciated the distinction between informative and emotive criteria. To me, it felt like a more in-depth and actionable version of the Good Charts matrix. Based on the profile, I was able to focus my redesign on three specific, high-impact areas: completeness, intuitiveness, and engagement. I also found that this method is most powerful when supplemented with a clear audience analysis, which provides the necessary context for the entire critique.

### Audience & Effectiveness

The website explicitly targets a broad audience, as mentioned in its "About the Tracker" section. This broad scope makes it difficult to serve all groups effectively.
- The site is perfect for its expert audiences (policymakers, academics, and legal organizations). These users are there for deep-dive research and will find the thorough, specific data they need.
- The site is less useful for journalists and community members. This audience is likely looking for a quick snapshot and will not get it from the landing page. There is a lack of context necessary to understand the information.

### Overall Observations

The Eviction Lab website is a very strong and beautiful design. Its aesthetic is one of its strengths, featuring a clean layout with striking color choices that should be retained in my redesign. The visualization is very truthful, with data collected by the Eviction Lab itself. The use of large, bold callout numbers is also highly perceptible and effective at drawing the eye.

However, the website's primary weakness is that it has a very wide intended audience. Thus, there is a disconnect between its presentation of data and the general (layman) audience's ability to takeaway information. The main issue for me is that there is a high need for users to scroll for important information, separating the key callout numbers from the map and state-specific data.

### Redesign Focus & Next Steps

Based on my critique, I'm not going to try to build something "better" by starting from scratch. That's not the point. The site is beautiful and the data is vital. My focus is to make the existing design more functional by **telling a story without scrolling**.

My idea is to make the map more dynamic. Instead of having it as a static picture with links further down the page, I want to make the map the primary filter. I think a user should be able to click on a state or city (or multiple of them) and immediately have the callout numbers on the left and the second visualization update to show the relevant data. This would consolidate the information, remove the need to scroll, and provide the immediate context currently missing.

*Note:* Instead of redesigning every visualization, this redesign focuses on the key components that impact the initial user experience, specifically for the general (layman) audience.

## Step Three: Sketch and Iterate a Solution

Three drafts were created, all on Tableau. However, only [draft 2](#draft-2) and [draft 3](#draft-3-pre-class-feedback-version) are included below. I put both of them in step 3 so that step 4 can be focused on feedback from our in-class critique.

### Draft 2 Feedback & Changes

My second draft is found below. The goal was to build out the main filtering action (connecting the map to the charts) and test the bar chart concept against the original line chart.

<div class='tableauPlaceholder' id='viz1762602280914' style='position: relative'><noscript><a href='#'><img alt='Dash ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ev&#47;EvictionsintheUSA-Sketch&#47;Dash&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='EvictionsintheUSA-Sketch&#47;Dash' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ev&#47;EvictionsintheUSA-Sketch&#47;Dash&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1762602280914');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width='850px';vizElement.style.height='827px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

I did a single feedback session for Draft 2. For this session, I wanted to focus on first impressions. Because of this, I sought insights from my friend—a male graduate student studying computer science and unfamiliar with both data analytics and evictions—since he wouldn't necessarily know what people in the TSWD class would look for.

| Question                              | Interview 1                   | Resulting Change from Draft 2 to Draft 3   |
|---------------------------------------|-------------------------------|-------------------------------|
|10 second test - What was the first thing that caught your eye?|The map and the big numbers caught my eye, but I could not focus on it due to the amount of text.|Reduced text per textbox.|
|10 second test - What do you think this dashboard is about?|The dashboard is about evictions and the number of landlords? Not sure what a moratorium is. The text under the big numbers was small. There were 34 states? Not sure, there was a lot of text and the first sentence's wording confused me.|Increased text size, all text has a minimum size 12. Reduced text to one-liners. Moved sources to a tooltip.|
|*(After noticing user did not intuitively interact/hover)* What would have made it clearer to you that the visualization is interactive?|Instant feedback would be nice so it is clear that it can be clicked.|Due to the use of Tableau Public, I could not find a workaround for instant tooltips (despite it being seen in the server version). Instead, I added a pointer icon with instructions. The hope is that a user would click the pointer icon.|
|What errors did you run into?|I was able to switch from months to years and quarters. Some of the month labels were also not visible. The baseline did not seem to change based on that. The time filter was hard to use too.|The drill down was not meant to be there and was fixed by creating new `Month` and `Year` fields. Continous `Month` was added to ensure all month labels would be visible. Time filter was removed to reduce clutter.|
|If you could change one thing about this dashboard to make it clearer, what would it be?|I would change the dots to be the same size, it was hard to click and see smaller dots. The color of the red bars were also unclear because the word "it" was used, but I don't know what "it" refers to.|Accepted suggested for dot size. Changed sentence structure to include "monthly baseline" in the red text as a legend.|
|Do you have any other comments|Scrolling made it difficult to see everything. It would be nice if black text was used instead of gray. The bars were also too thin|Adjusted height so that everything will fit in one frame and bars will appear thicker. This also greatly improved text size. Gray text was maintained to not distract and add too many colors.|

### Draft 3 (Pre-Class Feedback Version)

Based on the feedback from Draft 2, I created this third draft to bring to class. The changes focused on reducing text, improving clarity, and optimizing the layout to fit on a single, non-scrolling screen. I also included a breakdown of the key decisions that informed the pre-class version (from both Drafts 2 and 3).

<div class='tableauPlaceholder' id='viz1762831560665' style='position: relative'><noscript><a href='#'><img alt='Dash ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ev&#47;EvictionsintheUSA-Sketch3&#47;Dash&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='EvictionsintheUSA-Sketch3&#47;Dash' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ev&#47;EvictionsintheUSA-Sketch3&#47;Dash&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1762831560665');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width='850px';vizElement.style.height='677px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

### Points on the Map

When I was working on my first draft, one of the first things I did was adding a size scale for the city markers to show where the major hotspots were. However, I removed this from my third draft because I did not want to compare things that shouldn't be compared due to population sizes (ex. the circle in Pittsburgh vs the circle in New York City). Based on initial usability testing, the different sizes also made clicking smaller dots difficult.

During my second draft, I decided to remove the secondary circle that was creating the bullseye effect. I realized that it was unnecessary and adding clutter to the map. I also lowered the color's opacity, surrounding it with a white circle to better distinguish with points that are close to each other. The second draft is also where I turned the map into a filter using Tableau Actions. I had one Action that was filtering based on which states are selected and another one for cities. This results in changes for the callout statistics and the bar chart.

### Choosing Chart Types

The original website used a line chart, but I decided early on to use a bar graph (whether it was based on months, quarters, or years was a harder decision). The reason I chose the bar graph was because the original line chart felt like having to mentally calculate the gap between two jagged, moving lines (filings vs. baseline). I found seeing immediately which bars were above the baseline to be very beneficial. To add clarity, I also used a window function to color the bars when above the monthly baseline. 

### Context

I added text on the right side of the visualization to talk about federal eviction moratoriums, which I didn't know about until I looked up information on when eviction filings dropped. In my third graph, I decided to drop the word "moratorium" after feedback saying that many people may not know the word.

Another comment I received was to reduce the amount of text, as it was very dense. To reduce the cluttering, I used tooltips to add additional information, including sources and hover instructions. I also shortened sentences where I could. I felt that context was necessary because I was <u>very</u> confused when I was trying to recreate the graphs because I couldn't understand what some of the elements were for. I have learned since then and decided to add what I learned into the visualization. These include:
- What constitutes the colors on the bars
- What the baseline is referring to
- How many filings per year there were beyond percentages of the baseline

## Step Four: Test the Solution

I used Draft 3 during our in-class discussion to conduct a new round of usability testing and to see if the changes were successful. Questions I asked included the following:
- 10 second test: Take a quick look at this. What's the main story this dashboard is trying to tell you?
- Who do you think is the intended audience for this?
- Is the interactability intuitive? What was the first thing you wanted to click or hover on?
- What are your thoughts on the colors, specifically on the bar graph? Are there any special meanings?
- How would you find the eviction data for just your home state?
- What do you think is the reason for the surge?
- What's one thing you find confusing, or one thing you wish you could do that you can't?

### Draft 3 Feedback and Changes

Four graduate students from different fields were interviewed at the same time. General themes were summarized in the table below.
- **A**: Product Research and Psychology major with no data visualization experience
- **B**: Information Systems major with no data visualization experience
- **C**: Building Performance / Architecture major with no visualization experience, but data experience
- **D**: Public Policy and Management (Flagship) major with some data experience

| Theme / Component | Synthesized Feedback | Changes Made |
| :--- | :--- | :--- |
| **First Impression** | All users were impressed at the initial sketch (saying "wow"). In 10 seconds, it was hard to get an idea of what the information meant. User A said that they saw the big numbers, but not sure what they meant. User C saw the map and was curious about what the dots were, and saw the "Monthly Eviction" text. User D could not remember seeing a title, but knew that it was evictions. User D saw the map, many bars, and some color differences. | The design was significantly simplified to reduce cognitive load. Colors were used more sparingly, only on the most important items. |
| **Main Title & Story** | According to User D, the title wasn't functioning as a strong "headline." It "doesn't sound like a title" and needed a "stronger descriptor." Additionally, the title (referring to the bar graph title) was tiny. The main story wasn't immediately obvious in the 10-second test. | The main title was completely rewritten to be a strong, active headline: "Eviction filings pass pre-pandemic levels". The font size was dramatically increased to make it the first and most dominant visual element, clearly stating the dashboard's main story. The colors of the callout numbers were removed, and instead, the headline's color was changed. |
| **Audience** | User D assumed that it was for policymakers, but also stated that it looked accessible, but not clear who it was for. User C said that it looked like interesting information anyone should know about. | Although the group thought that this was a flaw (since they were expecting a single audience type), this actually confirmed the design was on the right track for its target general audience. All subsequent changes (simplifying text, clarifying the story) were made to better serve this "accessible to anyone" goal. |
| **Interactivity** | Users were not clear on *how* to interact and that they *could* interact. According to Users A and C, the pointer icon on the map was "not clear." User A suggested hovering for information, rather than click on states and cities, since hovering is very human. A suggestion was to "maybe add pointers to say to click." | The Draft 3 implementation already was using hover instead of just click, but it did not show quickly on Tableau Public. Hover filtering was tested but made the visualization "dizzying" and had performance issues. Therefore, the unclear pointer icon was replaced with an explicit, clear instruction on the map itself: "Click on one of our tracked states or cities" with a visual arrow. This was also used as a legend for the map since some users thought it was a heat map. |
| **Color Strategy** | This was the most confusing point. Users were "confused by colors" and asked if they were all related (e.g., the orange bars and the map dots). User D suggested to use color more strategically. User C suggested to use a different color for the single orange bar and "grey out the bars" to make it stand out. | This feedback was implemented directly. The complex color scheme was removed. I removed the dark blue background color. Gray was used for all bars below the baseline and red for bars that pass the baseline. |
| **Text & Wording** | The explanatory text was seen as weak. User D suggested adding the word "moratorium" to explain the ban (did not read the text to the left of the graph explaining it because it was too long). When asked if "prevented evictions" was hard to read, User D said yes. When asked if "eviction ban" would make more sense, User D agreed. | The longer paragraph of text was deleted. It was replaced with a single, scannable sentence that uses the stronger suggested wording: "The federal eviction ban lasted from May 2020 to August 2021." This provides all necessary context on top of the graph it was giving context for. A very light dotted box was also put around those months on the bar chart to mark it clearly, without overwhelming the user. |

After multiple rounds of usability testing, I found that the constraints of sticking with the original website's color scheme were holding me back. The feedback was clear: the colors were confusing and didn't guide the user. I made the decision to break from a strict replication of the branding and instead use color strategically. While the new design still matches the organization's branding (using its orange-red shade and blue), it is not excessive and prioritizes clarity.

## Step Five: Build the Solution

<div class='tableauPlaceholder' id='viz1762969332851' style='position: relative'><noscript><a href='#'><img alt='Dash (Light) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ev&#47;EvictionsintheUSA_17624872587900&#47;DashLight&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='EvictionsintheUSA_17624872587900&#47;DashLight' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ev&#47;EvictionsintheUSA_17624872587900&#47;DashLight&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1762969332851');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width='850px';vizElement.style.height='677px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

### Summary

**I selected this project for both its challenge and its potential impact.** The original Eviction Lab site was already an amazing baseline, so the challenge wasn't to fix something broken, but to tell its story differently. As an aspiring health policy analyst, I think that the topic of eviction is very important, and this redesign was an opportunity to engage with the data in a new way.

This project was an exercise in moving a design from a **multi-page data repository to an interactive single-page data story**. My initial critique of the original site was that it worked perfectly for experts but failed its general audience. The effectiveness profile was very helpful in pinpointing the areas where I could improve the original visualization: completeness, intuitiveness, and engagement. My redesigned dashboard successfully tackles this by telling the complete story on one page. The goal was to give a journalist or community member the main takeaway without having to leave the current page they were on.

To achieve this, I framed the visualization around the pandemic and the federal eviction ban. The dataset (from 2020-2023) showed a clear narrative: the dramatic, suppressive effect of the federal eviction ban and the subsequent surge as filings climbed back up, eventually surpassing pre-pandemic levels.

The dashboard includes a map showing all the states and cities tracked by the Eviction Lab. It also shows callout statistics on the total number of evictions since August 2021 and most recent number of evictions (August 2023). Most importantly, it shows month-by-month comparisons of the eviction filings as a percentage of the baseline from pre-pandemic levels. Raw numbers can also be seen if the user hovers over the bars.

Users can click on specific states and cities, showing them the updated numbers for total and latest monthly evictions. This also updates the bar graph where users can clearly see where monthly evictions exceeded baseline levels.

### Main Changes

To tell the story, I made several key choices that differ from the original:
- **Strong, Clear Headline**: The title itself tells the story: "Eviction filings pass pre-pandemic levels." This immediately gives the user the main insight.
- **A Bar Chart, Not a Line Chart**: I specifically chose a bar chart over the original's line chart. While a line chart is technically correct for time-series data, it failed to show the story clearly of where the monthly evictions exceeded the baseline. It allows for an instant comparison: are the bars above or below the baseline? The red-colored bars make the "surge" more visible.
- **Provided Context**: Instead of dense paragraphs of text, the entire "why" for the chart's shape is explained in a single, clear sentence: "The federal eviction ban lasted from May 2020 to August 2021."
- **Action-Oriented Map**: The map is now used as the dashboard's main filter, with a clear callout to invite the user to click and explore the data for their own state.

<div style="display:flex; flex-wrap:wrap; gap:1rem; justify-content:center; align-items:flex-start;">
    <img src="/images/posts/tswd/critique_by_design/Select_City.png" alt="City" style="max-width:48%; width:48%; height:auto;" />
    <img src="/images/posts/tswd/critique_by_design/Select_State_Tooltip.png" alt="State" style="max-width:48%; width:48%; height:auto;" />
</div>

### About the Process

The process taught me three key lessons:

1. Trust the Feedback: Functional drafts can improve by giving them clarity. While a tool may feel usable to me (someone who spent a significantly longer amount of time to familiarize with the website), it can bring confusion for new users. The user confusion around color and text was valuable. Without it, I would have created a dashboard that, while interactive, was still too dense and confusing.

2. Prioritize the story, not just the rules: I chose to break the rule of using a bar graph instead of a line chart to compare values to a baseline. I found this to be more important to my story than showing a continuous trend. The bar chart's "above/below" clarity was the right tool for the job.

3. "Keep It Simple, Stupid" is a process: My first interviewee told me to follow KISS. I didn't know how to make the dashboard simple until I first made it complicated. I had to add all the text, colors, and features first, then use usability testing as a filter to aggressively remove or simplify everything that didn't serve the main story.

## References

Data from Makeover Moday: Monthly Eviction Filings in America (https://data.world/makeovermonday/2023w38)

Eviction Lab. *(n.d.)*. Eviction Tracking System. Retrieved November 8, 2025, from https://evictionlab.org/eviction-tracking/.

Few, Stephen. *(2017)*. “Data Visualization Effectiveness Profile.” Retrieved November 8, 2025 from http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf

Smith, L. *(2023)*. Effects of the Federal Eviction Moratorium Being Lifted: The Feared Wave of Evictions That Never Hit. Retrieved from https://law.pepperdine.edu/surf-report/posts/effects-of-federal-eviction-moratorium-being-lifted-lindsey-smith.htm

## AI acknowledgements

AI was not used for this project.