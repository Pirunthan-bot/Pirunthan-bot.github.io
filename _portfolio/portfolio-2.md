---
title: "Mind The Gap: Analysing income desparities in New Zealand"
excerpt: "An infographic analysing income desparity across various metrics<br/><img src='/images/Mindthegap.png'>"
collection: portfolio
---

During my time as a university student, I enrolled in the very course I now teach. As part of the course, I created an infographic to highlight income disparity within New Zealand and compare it to other countries. This project aligned with the UN sustainability goal of reducing inequality.

The focal point of the visualization is the Gini Coefficient, a statistical measure of income inequality. The infographic begins by presenting New Zealand's standing in terms of the Gini Coefficient and then delves into the implications of this ranking. It explores disparities across different regions, genders, and income deciles within New Zealand.

The final section of the infographic discusses initiatives aimed at closing the gap and reducing inequalities in the nation. To effectively tell this story, I employed a variety of visualizations to engage the audience, complemented by supporting text that provides necessary context without overwhelming viewers.

Unlike dashboard design, infographic design requires more explanatory text to be informative while maintaining audience engagement with compelling visuals. Since infographics are intended to be enduring, it's crucial to strike the perfect balance between text and visuals, ensuring that each element is focused and within the scope of the overall narrative.   
 
<script type="module" src="https://public.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js"></script>

<!-- 
Initialize the API as part of your HTML code by using the <tableau-viz> web component. 
After linking to the API library, the following code is all you need to embed a Tableau view into your HTML pages.
-->

<style>
  #tableauViz {
    width: 100%;
    height: 60vh; /* Adjust this value based on the desired height relative to the viewport height */
    border: none; /* Optional: remove border if there's any */
  }
</style>

<tableau-viz id="tableauViz"       
  src='https://public.tableau.com/views/Group_22INFOGRAPHICFinal_0/Draft1'      
  toolbar='bottom' hide-tabs>
</tableau-viz>