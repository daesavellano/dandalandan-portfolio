---
title: "Critique by Design"
featured_image: ../assets/images/featured/TSWD_Evictions_Draft_2.png
date: 2025-11-08
draft: false
type: "page"
tags: "Template"
---

<center><h1>Monthly Eviction Filings in America</h1></center>

- [Step One: The Visualization](#step-one-the-visualization)
- [Step Two: The Critique](#step-two-the-critique)
- [Step Three: Sketch a Solution](#step-three-sketch-a-solution)
- [Step Four: Test the Solution](#step-four-test-the-solution)
- [Step Five: Build the Solution](#step-five-build-the-solution)

<!-- I will likely add the final visualization on top as well so it's not lost in the weeds -->

<!-- _For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance. This template does not include all guidance mentioned on the assignment page._ -->

## Step One: The Visualization

For this redesign, I am primarily looking at the landing page and the first graph you can see when you scroll on the [Eviction Tracking System](https://evictionlab.org/eviction-tracking/) by [The Eviction Lab](https://evictionlab.org/about/) at Princeton University. This is based on data from the [2023/W38 Makeover Monday challenge](https://data.world/makeovermonday/2023w38).

- The visualization is the first thing a user sees on the tracking page, featuring a map of the United States and large summary statistics.
- The second visualization can be seen after scrolling to the next page.
- Beyond the screenshot, there are additional visualizations that can be revealed by scrolling to the “filings by location" section.

<center><a href="https://evictionlab.org/eviction-tracking/"><img src="/images/posts/tswd/critique_by_design/Eviction_Lab_2025.png" alt="2025 Eviction Lab Screenshot" style="max-width: 70%; height: auto;" /></a></center>

### Why I chose this visualization
- **As a designer and storyteller,** I thought that redesigning this visualization would be a fun challenge. I added the constraints of matching the organization’s branding. It was already a lovely baseline, and my goal is not to top it. Instead, my main goal is to make it more consolidated and add a story layer.
- **As an aspiring health policy analyst,** The topic of eviction is very important, and the dataset I was able to get from Makeover Monday only had data from 2020-2023, with the baseline being pre-pandemic levels.

## Step Two: The Critique

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

### Overall Observations

The Eviction Lab website is a very strong and beautiful design. Its aesthetic is one of its strengths, featuring a clean layout with striking color choices that should be retained in my redesign. The visualization is very truthful, with data collected by the Eviction Lab itself. The use of large, bold callout numbers is also highly perceptible and effective at drawing the eye.

However, the website's primary weakness is that it has a very wide intended audience. Thus, there is a disconnect between its presentation of data and the general (layman) audience's ability to takeaway information. The main issue for me is that there is a high need for users to scroll for important information, separating the key callout numbers from the map and state-specific data.

### Audience & Effectiveness

The website explicitly targets a broad audience, as mentioned in its "About the Tracker" section. This broad scope makes it difficult to serve all groups effectively.
- The site is perfect for its expert audiences (policymakers, academics, and legal organizations). These users are there for deep-dive research and will find the thorough, specific data they need.
- The site is less useful for journalists and community members. This audience is likely looking for a quick snapshot and will not get it from the landing page. There is a lack of context necessary to understand the information.

### Redesign Focus & Next Steps

Based on my critique, I'm not going to try to build something "better" by starting from scratch. That's not the point. The site is beautiful and the data is vital. My focus is to make the existing design more functional by **telling a story without scrolling**.

My idea is to make the map more dynamic. Instead of having it as a static picture with links further down the page, I want to make the map the primary filter. I think a user should be able to click on a state or city (or multiple of them) and immediately have the callout numbers on the left and the second visualization update to show the relevant data. This would consolidate the information, remove the need to scroll, and provide the immediate context currently missing.

*Note:* Instead of redesigning every visualization, this redesign focuses on the key components that impact the initial user experience, specifically for the general (layman) audience.

## Step Three: Sketch and Iterate a Solution

Three drafts were created, all on Tableau. However, only [draft 2](#draft-2) and [draft 3](#draft-3-pre-class-feedback-version) are included below. I put both of them in step 3 so that step 4 can be focused on feedback from our in-class critique.

### Draft 2

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

### Draft 2 Feedback & Changes
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

I used Draft 3 during our in-class discussion to conduct a new round of usability testing and to see if the changes were successful. Questions I am interested in asking to see comprehension include the following:
- 10 second test: Take a quick look at this. What's the main story this dashboard is trying to tell you?
- Who do you think is the intended audience for this?
- Is the interactability intuitive? What was the first thing you wanted to click or hover on?
- What are your thoughts on the colors, specifically on the bar graph? Are there any special meanings?
- How would you find the eviction data for just your home state?
- What do you think is the reason for the surge?
- Is there anything you find surprising or confusing?
- What's one thing you find confusing, or one thing you wish you could do that you can't?

### Draft 3 Comments and Changes

<!-- _Don't identify or share personally identifiable information (PII) about the people you spoke to._ -->


| Question                              | Interview 1 | Interview 2 |
|---------------------------------------|-------------|-------------|
|1|             |             |
|2|             |             |
|3|             |             |
|4|             |             |
|5|             |             |

Synthesis: 

<!-- _What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._ -->

## Step Five: Build the Solution

<!-- _Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._ -->

## References
<!-- _List any references you used here._ -->

Data from Makeover Moday: Monthly Eviction Filings in America (https://data.world/makeovermonday/2023w38)

Eviction Lab. *(n.d.)*. Eviction Tracking System. Retrieved November 8, 2025, from https://evictionlab.org/eviction-tracking/.

Few, Stephen. *(2017)*. “Data Visualization Effectiveness Profile.” Retrieved November 8, 2025 from http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf

Smith, L. *(2023)*. Effects of the Federal Eviction Moratorium Being Lifted: The Feared Wave of Evictions That Never Hit. Retrieved from https://law.pepperdine.edu/surf-report/posts/effects-of-federal-eviction-moratorium-being-lifted-lindsey-smith.htm

## AI acknowledgements
<!-- _If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._ -->