---
layout: post
author: Jens
title: <html>&#91;SCMCS&#93;</html> SCM Case Studies - SCM Globe
description: In this series I am going to discuss my experience with SCM Globe to construct, manage and analyze supply chains. The complexity will increase with each post, including tools from data analysis, optimization and the corresponding tools in python and Libreoffice.
date: 2020-06-10T10:20:00Z
img: trucks-parked.jpg
tags: [SCM, Modeling, Simulation]
---

How to get a foot into the door of supply chain management? That was the question I asked myself several times while doing multiple online courses on the subject. The optimization topics were nice, the mathematics often quite involved (which I loved!) but in the end it remained theoretical since most companies were made up, some routings mathematically impossible and the network component often not included in the models.
Then I stumbled upon <a href="https://www.scmglobe.com/">SCM Globe</a> while looking for SCM case studies and had the time of my life. (This is not sponsored, I just enjoyed it very much). The platform gave me a possibility to develop a SCM case study portfolio while showing of my data analytics skills. This series is meant to show off my portfolio and help others to follow this path.

# SCM Globe and my experience using it 
So, what is SCM Globe and what can we do with it? Starting with the disclaimer that it is not free seems to be necessary at this point. But you can get (for the time being) a free version depending on your status. 
In my opinion it is very intuitive to handle but the getting started videos also add a lot of value especially when you think about getting a trial version. My recommendation: Watch all the getting started videos beforehand to jump right into the good stuff as soon as your trial starts. In the end it is a very simplistic and rapidely explained UI but with nice modelling possibilities.

# The Cincannati Challenge

The first case study proposed by SCM Globe is the <a href = 'https://www.scmglobe.com/cincinnati-seasonings/'>Cincannati Challenge</a>. Basically a factory, a distribution center (DC) and a few shops. The goal? Try to maintain the supply chain for 30 days without interruption. Possible causes?
 1. A shop runs out stock
 2. DC runs out of stock
 3. Factory does not produce enough
 4. One of the above exceeds its maximum inventory level.

Since after importing the initial setting provides already some routes and vehicles connecting all of the above mentionned entities of the supply chain. But are they effectively structured and functional? 
<iframe src='{{site.baseurl}}/assets/img/Edit_Screen.png' width='100%' height='565px' frameborder='0'> </iframe>
Lets run a simulation 
<iframe src='{{site.baseurl}}/assets/img/Design_Simulation.png' width='100%' height='565px' frameborder='0'> </iframe>
Evidently, the shop in Ft Wayne becomes overstocked. But what are the initial levels? How many stock does the shop receive each day or within a to be defined time period? Fortunately, we have a tool to analyze the behavior of our chain: spreadsheets!!!   
We might also click on every entity in the model and collect the information bit by bit but spreadsheets yield a holistic perspective in a concise way. So lets benefit from it.  
<iframe src='{{site.baseurl}}/assets/xlsx/Simulation_Cin_basic.html' width='100%' height='565px' frameborder='0'> </iframe>
