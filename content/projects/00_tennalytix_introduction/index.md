---
title:  "🎾🔍 Tennalytix (1/5): Introduction Into My Tennis Analytics Project"
date: 2021-02-10T11:39:10+02:00
publishdate: 2021-02-10T11:39:10+02:00
image: "/images/blog/2.jpg"
tags: ["tennalytix"]
comments: false
postsummary: "Is it possible to generate 3d tracking data based on 2d Youtube tennis videos? Can we use the data to generate player insights? Those were questions that I tried to tackle in this side project."
---

# Introduction
In my master thesis project at Imperial, I worked with tennis tracking data of professional players that was not publicly available. Analytics in tennis was lacking behind compared to other sports due to limited data access. My strong believe was and is still that one can generate more insights from tracking data in tennis than one can do in other sports. In this personal side project, my goal was to create 3d tracking data based on 2d Youtube Videos to then analyse the data. 

# Series Overview
This is the first blog post of a series of blog posts in which I describe how I tracked ball and player coordinates, processed the data into 3d tracking data and created a dashboard using Dash to surface the results. 

This blog post series contains the following parts: 
- [🎾🤖 Tennalytix (2/5): Track Pixel Positions Through Deep Learning]({{< ref "/projects/01_track_pixel_positions" >}} "About Us")
    - How I tracked player and ball pixel positions over time based on Youtube videos using several deep learning models
- [🎾💻 Tennalytix (3/5): Create Tkinter GUI To Manually Overwrite Predictions]({{< ref "/projects/02_tkinter_gui" >}} "About Us")
    - How I created a GUI (graphic user interface) using Tkinter to be able to load predictions from deep learning models, check and correct predictions
- [🎾🏹 Tennalytix (4/5): Create 3d Spatiotemporal Tracking Data]({{< ref "/projects/03_create_3d_data" >}} "About Us")
    - How I created 3d spatiotemporal (3-dimensional data over time) tracking data using pixel location data
- [🎾📊 Tennalytix (5/5): Visualising Insights using Plotly Dash]({{< ref "/projects/04_tennalytix_dashboard" >}} "About Us")\   
    - How I created 3d spatiotemporal tracking data using pixel location data

# Conclusion
The project required a lot of time next to work and was technically challenging. However, in the end, it was totally worth it. I increased my computer science as well as Data Science knowledge in so many different ways and encourage everybody to start a side passion project. 

