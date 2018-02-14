---
layout: post
title:  "Designing the NBER website"
date:   2018-01-03
---

**Disclaimer**
Redesigning websites from the outside is a bad idea. I do not know the constraints of the web developers and designers about the website. Which means any design I propose is unlikely to be implemented because it is not realistic. Web design is challenging. However, doing redesigns can be a fun exercise as long as I able to properly place my design in context.

### Motivation
The National Bureau of Economic Research (NBER) is a non-profit economic research organization based in the United States. The research that comes from economists affiliated with the NBER is interesting and insightful. I enjoy reading papers from the NBER but I do not enjoy visiting the site. The site is not responsive and not user friendly. Moving to a more responsive site could see increases in traffic and will remove the need to maintain a mobile site. 

### Metrics
Website metrics can be useful indicators on what changes need to happen. I tend to use website metrics from Google. I do not know enough about the inner workings of Googl's webiste tests so I take the results with a grain of salt. 

The results from the "Test your mobile speed" for [nber.org](nber.org) shows that the site does not pass the usability test and that the site loads around 6 seconds on 3G. Test: [Test My Site](https://testmysite.thinkwithgoogle.com/)

### Steps

The three meta tags are the building blocks for a more responsive and user-friendly website. Just copying the code below and placing into the existing website will not work. I have tried doing something similar and it threw off

```
<head>
<meta charset ="utf-8">
<meta http-equiv="x-ua-compatible" content="ie-edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>The National Bureau of Economic Research</title>
</head>
```


