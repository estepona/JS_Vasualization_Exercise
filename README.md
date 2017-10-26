## Vasualization with JavaScript
This repository contains my exercises and projects on visualizations with JS libraries

### Structure
- **1 ECharts**

  This folder contains exercises on [ECharts](http://echarts.baidu.com/index.html) library, a powerful yet easy-to-use JS visualization library powered by Baidu. 
  
  Below is one simple example of what ECharts can make.
  ![flower chart](https://raw.githubusercontent.com/estepona/Visualization_JavaScript/master/1%20ECharts/1%20Simple%20Plots/5%20%E8%8A%B1%E7%93%A3%E9%A5%BC%E5%9B%BE.png)
- **2 bilibili Analytics Tool**

  This tool I built in a course project takes in data collected from bilibili with a web crawler, and outputs a dashboard visualizing the most important measurements of a uploader's historical activities. 

  ![bilibili screenshot](https://raw.githubusercontent.com/estepona/Visualization_JavaScript/master/2%20bilibili%20Analytics%20Tool/bilibili.png)
  
  Click **[here](http://www.terpconnect.umd.edu/~bz0045/INST741_finalProject/bilibili_dashboard.html)** to have a quick look at the interactive dashboard. It is currently hosted on my school's server, and last updated on May 8, 2017.

  In the folder you can find three files: a mind map of the overall organization of data structure, a Python web crawler, the dashboard(.html), and a json file that stores all the data collected with the web crawler. To use this tool, simply download three files, run the web crawler with the uploader's ID of your choice, and open the dashboard in a server environment. To run it locally, type the following command in a terminal:

  `python -m http.server` (assuming you have Python3)
  
  And then open the browser, open a localhost, and you should be able to see it.


