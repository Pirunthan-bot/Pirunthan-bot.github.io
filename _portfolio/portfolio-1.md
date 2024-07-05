---
title: "Facebook Messenger Analysis"
excerpt: "Analysing facebook messenger chat data leveraging sentiment analysis<br/><img src='/images/Chatlog.png'>"
collection: portfolio
---

One day while browsing Facebook, I discovered the option to request a full download of all my data. Curious about the extent of Facebook's data tracking, I requested the data, which arrived in JSON format. The sheer volume of recorded data astonished me, and I felt compelled to visualize it to tell an interesting story.

I focused on the chat logs, as they offered the most potential for a cohesive narrative. Specifically, I was interested in analyzing the chat behavior between my wife and me. To make the data more manageable, I limited the scope to one year’s worth of messages.

Starting with exploratory analysis, I identified a key insight: the volume of messages. This provided a solid foundation to delve deeper into our chat behavior. To analyze the messages without revealing sensitive information, I decided to run sentiment analysis on the chat history. I visualized the sentiment distribution in a histogram, which revealed who was more positive or negative in our messages.

To showcase the power of Tableau, I highlighted the seasonality of our conversations using a radial chart. I maintained a consistent color scheme of blue and pink to compare various categories, which tied the story together nicely.

I often showcase this project during my lectures on conscious dashboard design, demonstrating to students the importance of thoughtful data presentation and the powerful insights that can be derived from well-crafted visualizations.
 
<script type="module" src="https://public.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js"></script>

<!-- 
Initialize the API as part of your HTML code by using the <tableau-viz> web component. 
After linking to the API library, the following code is all you need to embed a Tableau view into your HTML pages.
-->

<style>
  #tableauViz {
    width: 100%;
    max-width: 100%;
    height: 70vh; /* Adjust this value based on the desired height relative to the viewport height */
  }
</style>

<tableau-viz id="tableauViz"       
  src='https://public.tableau.com/views/ChatLogAnalysisv2/Dashboard1'      
  toolbar='bottom' hide-tabs>
</tableau-viz>