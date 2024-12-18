| [Home Page](https://maitri-surti.github.io/maitri-surti-portfolio/) | [Visualizing Government Debt](https://maitri-surti.github.io/maitri-surti-portfolio/dataviz2) | [MakeOverMonday](https://maitri-surti.github.io/maitri-surti-portfolio/makeOverMonday) | [Final Project Part I](https://maitri-surti.github.io/maitri-surti-portfolio/final_project_MaitriSurti) | [Final Project Part II](https://maitri-surti.github.io/maitri-surti-portfolio/final_project_part2_MaitriSurti) | [Final Project Part III](https://maitri-surti.github.io/maitri-surti-portfolio/final_project_part3_MaitriSurti) |

# Assignment: Visualizing government debt using Tableau

## Part one: Working with web-based visualization tools and data
![General government debt](https://github.com/user-attachments/assets/7e7b734f-9e0c-42f9-a6ef-7c6e75363b7f)

## Part two: Working with Tableau
<div class='tableauPlaceholder' id='viz1730428471902' style='position: relative'><noscript><a href='#'><img alt='Government Debt-to-GDP Ratio Source: General government debt. (n.d.). OECD. https:&#47;&#47;www.oecd.org&#47;en&#47;data&#47;indicators&#47;general-government-debt.html?oecdcontrol-3122613a85-var3=2023#top  ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;da&#47;dataviz2_17304284585290&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='dataviz2_17304284585290&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;da&#47;dataviz2_17304284585290&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1730428471902');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                      
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## Part three: Create your own Visualization

In examining the government debt-to-GDP ratio data across countries, we created three visualizations in Tableau: a bar chart, a heat map, and a line graph (the third visualization) to explore the data. Each data visualization serves a different purpose. The bar chart provides a direct comparison of government debt ratios among countries at specific points in time, making it useful for comparing individual years but less effective for tracking changes over time. The highlight table, on the other hand, conveys the intensity of debt-to-GDP ratios across countries and years through color gradients, allowing viewers to quickly identify years of high or low ratios across regions. However, it lacks the precision of seeing specific trends or fluctuations.


The line graph visualizes the average government debt-to-GDP ratios of continents from 1995 to 2019. Each line represents a continent, with color-coded lines distinguishing between North America, South America, Europe, Asia, and Australia. The vertical axis shows the average debt-to-GDP ratio. By focusing on continental averages, I aimed to highlight how different regions experienced changes in government debt relative to GDP over time. Having all the individual countries in the line graph made it clustered and impossible for the users to gain insights from the graph. 

I chose line graph because I wanted to bring forward both the general trends and specific variations, which are harder to analyze in other formats. Initially I thought of using gradient colors for the graph to look better but then I realized that using colors with less contrast can pose a challenge for the users to interpret the graph effectively. Hence, I used very varied and different colors for all the continents to avoid any sort of confusion. This choice of using line graph grouped by continents and varied colors ultimately provides a clearer picture of each continent's fiscal health trajectory.

[Source: General government debt. (n.d.). OECD.](https://www.oecd.org/en/data/indicators/general-government-debt.html?oecdcontrol-3122613a85-var3=2023#top)

<div class='tableauPlaceholder' id='viz1730501069405' style='position: relative'><noscript><a href='#'><img alt='Government Debt-to-GDP Ratio Trends by Continent (1995-2019) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;pa&#47;part3dataviz&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='part3dataviz&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;pa&#47;part3dataviz&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1730501069405');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
