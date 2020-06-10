---
layout: post
title: QS1 | A New Project
date: '2016-11-09T16:42:00.000Z'
author: VizScribbler
tags:
- data
- visualisation
- tableau
- data viz
- quantified self
- dashboard
modified_time: '2016-11-09T17:02:00.705Z'
thumbnail: https://2.bp.blogspot.com/-aW4xfgKujAQ/WCNOH2MclRI/AAAAAAAABIQ/KBhNPIDwEBkgZ4aBsrrLqkPujgZzGDH8QCLcB/s72-c/QS.png
blogger_id: tag:blogger.com,1999:blog-5138343082934398153.post-6603614953574972138
blogger_orig_url: https://vizscribbler.blogspot.com/2016/11/qs1-new-project.html
---
<i>So, some of these images are broken, and it's been a few years and I'm not sure what they were.. so.... sorry..</i>

When I joined the Information Lab, the legend who is <a href="http://twitter.com/tableautim" target="_blank">Tim Ngewna</a>&nbsp;introduced the term "quantified self" to me. I'd heard of fitness tracking, but life tracking was a concept which was very new to me. Over the last 6-8 months, I've wanted to force myself to track something in my life - almost similar to the <a href="http://deardata.com/" target="_blank">Dear Data</a> &amp; <a href="http://www.dear-data-two.com/" target="_blank">Dear Data 2</a> projects<br /><br /><img alt="Image result for deardata" height="424" src="https://static1.squarespace.com/static/54eec73ee4b0ae0904da0e94/567a084a05f8e24bd8c0882a/567a084c05f8e24bd8c08832/1450838106323/Giorgia_DearData_52_Back.jpg" width="640" /><br /><br />When doing Dear Data 2, <a href="http://twitter.com/vizwizbi" target="_blank">Andy Kriebel </a>used a multitude of mobile applications to track something every week. For me, I didn't want to commit to something over just 7 days, and wanted a bit more data to play with. So my plan is to go through and track one thing every month and visualise it and see what I find out. I'll be using 28 days of data (because, well, February)<br /><br />This month, using a <a href="https://ifttt.com/" target="_blank">IFTTT </a>(if this, then that) recipe to log the temperature of where I am to Google Sheets every morning. So what I've done with this data is a really simple visualisation. The fields I had were;<br /><ul><li>Condition (cloudy/sunny/rain etc)</li><li>Sunrise at</li><li>High Temp</li><li>Low Temp</li><li>Temp</li></ul><div>Now, what's interesting (I think) is when I was getting this data logged, I wanted to look at the "sunrise" field - but when I got to looking at the data and testing, the story which popped out which I imagined would be interesting was to make a simple visualisation to show simply the temperature. Check out the image below.<br /><br /><div class="separator" style="clear: both; text-align: center;"><a href="https://2.bp.blogspot.com/-aW4xfgKujAQ/WCNOH2MclRI/AAAAAAAABIQ/KBhNPIDwEBkgZ4aBsrrLqkPujgZzGDH8QCLcB/s1600/QS.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="334" src="https://2.bp.blogspot.com/-aW4xfgKujAQ/WCNOH2MclRI/AAAAAAAABIQ/KBhNPIDwEBkgZ4aBsrrLqkPujgZzGDH8QCLcB/s640/QS.png" width="640" /></a></div><br />Given it's a temperature visualisation, I used a "thermometer" style chart, with the dot representing the daily low, and the Gantt showing the difference between high and low. The label itself is the simple daily temperature.<br /><br />When I finished the visualisation, I created the key (top right) - I love stuff like this, and I've been a huge fan of <a href="http://www.visualisingdata.com/2016/03/little-visualisation-design/" target="_blank">Andy Kirk</a>'s "the Little of Visualising Design" series. The key is a really nice simple visual way of understanding how to read the chart. It saves on text, and when done will can be super brief - Let me know what you think about my effort!<br /><br />After this point, and adding the text - I sat back and realised I had a lot of blank space at the bottom of the viz, so I added a few headline figures to add a bit more simple information to the viz.<br /><br />Please feedback on this visualisation; next month (or rather this month), I am tracking the amount of times I consciously look at a clock/the time.<br /><br /></div><div class="separator" style="clear: both; text-align: center;"><i>Check out the visualisation itself on Tableau Public <a href="https://public.tableau.com/views/QSTheTemperatureAroundMe/QS1?:embed=y&amp;:display_count=yes" target="_blank">here</a>.</i></div><div class="separator" style="clear: both; text-align: center;"><i><br /></i></div><div class="separator" style="clear: both; text-align: center;"><b>EDIT:</b></div><div class="separator" style="clear: both; text-align: center;">Since posting this blog, I sought out feedback from the excellent <a href="http://www.thedataschool.co.uk/" target="_blank">#DS4 group</a>&nbsp;and they gave some great ideas on how I could improve it. Find the changes on the Tableau Public here! (and check out the image to compare below)</div><div class="separator" style="clear: both; text-align: center;"><br /></div><div class="separator" style="clear: both; text-align: center;"><a href="https://2.bp.blogspot.com/-Xione7Jodx8/WCNWNpsXQeI/AAAAAAAABIo/34RONP8ZmWg8DfpAWBXMg8rt_GB5rOoNwCLcB/s1600/screencap.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="324" src="https://2.bp.blogspot.com/-Xione7Jodx8/WCNWNpsXQeI/AAAAAAAABIo/34RONP8ZmWg8DfpAWBXMg8rt_GB5rOoNwCLcB/s640/screencap.png" width="640" /></a></div><div class="separator" style="clear: both; text-align: center;"><br /></div><div class="separator" style="clear: both; text-align: center;">The feedback they gave was that the current temp (ie. the temperature at the point at which IFTTT was sending me the update) was confusing as a concept. Instead, I've now changed the labels to be the high and low, with the current temp not even used.&nbsp;</div><script type="text/javascript">                    var divElement = document.getElementById('viz1478708793230');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='1104px';vizElement.style.height='669px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>