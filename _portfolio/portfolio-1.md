---
title: "Facebook Messenger Analysis"
excerpt: "Analysing Facebook messenger chat data leveraging sentiment analysis<br/><img src='/images/Chatlog.png'>"
collection: portfolio
---


One day while browsing Facebook, I discovered the option to request a full download of all my data. Curious about the extent of Facebook's data tracking, I requested the data, which arrived in JSON format. The sheer volume of recorded data astonished me, and I felt compelled to visualize it to tell an interesting story.

I focused on the chat logs, as they offered the most potential for a cohesive narrative. Specifically, I was interested in analyzing the chat behavior between my wife and me. To make the data more manageable, I limited the scope to one year’s worth of messages.

Starting with exploratory analysis, I identified a key insight: the volume of messages. This provided a solid foundation to delve deeper into our chat behavior. To analyze the messages without revealing sensitive information, I decided to run sentiment analysis on the chat history. I visualized the sentiment distribution in a histogram, which revealed who was more positive or negative in our messages.

To showcase the power of Tableau, I highlighted the seasonality of our conversations using a radial chart. I maintained a consistent color scheme of blue and pink to compare various categories, which tied the story together nicely.

I often showcase this project during my lectures on conscious dashboard design, demonstrating to students the importance of thoughtful data presentation and the powerful insights that can be derived from well-crafted visualizations.

<div style="text-align: center;">
    <div class='tableauPlaceholder' id='viz1720162990356' style='position: relative'>
        <noscript>
            <a href='#'>
                <img alt='Dashboard 1 ' src='https://public.tableau.com/static/images/Ch/ChatLogAnalysisv2/Dashboard1/1_rss.png' style='border: none' />
            </a>
        </noscript>
        <object class='tableauViz'  style='display:none;'>
            <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
            <param name='embed_code_version' value='3' /> 
            <param name='site_root' value='' />
            <param name='name' value='ChatLogAnalysisv2/Dashboard1' />
            <param name='tabs' value='no' />
            <param name='toolbar' value='yes' />
            <param name='static_image' value='https://public.tableau.com/static/images/Ch/ChatLogAnalysisv2/Dashboard1/1.png' /> 
            <param name='animate_transition' value='yes' />
            <param name='display_static_image' value='yes' />
            <param name='display_spinner' value='yes' />
            <param name='display_overlay' value='yes' />
            <param name='display_count' value='yes' />
            <param name='language' value='en-US' />
        </object>
    </div>
</div>  

<script type='text/javascript'>
    var divElement = document.getElementById('viz1720162990356');
    var vizElement = divElement.getElementsByTagName('object')[0];
    if ( divElement.offsetWidth > 800 ) {
        vizElement.style.width='1654px';
        vizElement.style.height='1196px';
    } else if ( divElement.offsetWidth > 500 ) {
        vizElement.style.width='1654px';
        vizElement.style.height='1196px';
    } else {
        vizElement.style.width='100%';
        vizElement.style.height='727px';
    }
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
