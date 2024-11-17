| [Home Page](https://maitri-surti.github.io/maitri-surti-portfolio/) | [Visualizing Government Debt](https://maitri-surti.github.io/maitri-surti-portfolio/dataviz2) | [MakeOverMonday](https://maitri-surti.github.io/maitri-surti-portfolio/makeOverMonday) | [Final Project](https://maitri-surti.github.io/maitri-surti-portfolio/final_project_MaitriSurti) |

# Assignment: Critique by Design with Tableau (MakeoverMonday)

## Step one: choose a data visualization from MakeoverMonday
[Source: What Schools Create the Most Student Loans in the U.S.?](https://howmuch.net/articles/university-with-the-most-student-loan-originations-in-every-state)

![image](https://github.com/user-attachments/assets/896cf5e2-3306-4fdf-834f-f0b2731b7b6f)

### What the data visualization shows
This visualization shows the universities in each U.S. state with the highest student loan originations for the 2020-2021 academic year, illustrating both the total loan amounts and institution types. Using color-coding, it distinguishes between public, private nonprofit, and proprietary institutions, with darker shades indicating higher loan amounts. The map reveals notable patterns, such as Arizona State University ($568M) and Liberty University ($447M) having some of the highest student debt burdens. This data viz allows for quick comparisons across U.S states and highlights the financial challenges faced by students at different types of institutions across the country.

### Motivation to choose this data viz
As an international student, I found this visualization especially relevant and insightful, given my own experience navigating educational financing. Coming from abroad, I was eager to understand the student loan landscape in the U.S., where college debt is a significant factor for many students. This map helps me appreciate the scale of loan originations across different institutions, showing where student debt burdens are highest. Having gone through a similar process to finance my own studies, I can empathize with the financial pressures U.S. students face and see how these trends vary by institution and region. This visual highlights not only the importance of financial planning for higher education but also deepens my understanding of the financial commitments many of my peers have made to pursue their academic goals. I found this visualization particularly interesting because it highlights a surprising trend: the majority of loan originations are associated with public schools. I had initially expected private nonprofit schools to account for the highest number of loan originations, given their typically higher tuition costs and reliance on student loans. However, the data clearly shows that public institutions generate more loan originations, challenging my initial assumption and shedding light on the financial dynamics of public versus private education.

## Step two: critique the data visualization

### My critique about the data viz
Overall, what worked well is that the data viz has taken into account only one university per state which has the highest student loan origination in each U.S. state. This avoids cluster around the map and helps user draw conclusions of only the most important aspect rather than showcasing all the universities in that state. However, according to me what didn't work very well was the legend based on the type of university (public, private-non profit, proprietary). I think the legend is confusing for the users to understand. I also think that the data viz is not taking into account the population of a university to draw accurate conclusions. If I were to do something different, I would improve the legend for the segregation based on the type of university and maybe remove the university logo from each state as that is making the map look super clustered. Also, the northeaster states look very clustered and difficult to read.  Moreover, the 3 universities at the bottom right do not clearly state the location that they belong to, it looks like those are just randomly included (I had to google those universities to look for their location). For example, for the legend, I would probably have 3 different colors for the university types and have a stroke on each university with that color. Lastly, the borders between each state is not very distinguishable. It'd look better to have a thicker and clearer outline around the states. 

### Primary audience for the visualization
Education policy makers and government officials are the primary audience for this tool. For the primary audience, the data viz is fairly effective due to 2 main reasons:
1. By showing which universities generate the most student loan debt in each state, this visualization helps policy makers quickly identify institutions where debt burdens are highest. 
2. The color-coding by institution type (public, private-nonprofit, proprietary) provides a useful breakdown, allowing policy makers to assess whether certain types of institutions contribute more to student debt.
   
### Evaluating Stephen Few’s “Data Visualization Effectiveness Profile”
Evaluating the data visualization using Stephen Few’s “Data Visualization Effectiveness Profile” offers a structured, detailed approach for examining its strengths and areas for improvement, particularly regarding usefulness (8/10), completeness (6/10), perceptibility (5/10), truthfulness (7/10), intuitiveness (5/10), aesthetics (3/10), and engagement (6/10). I feel that it mostly covers all the necessary elements that would be useful in examining a data viz. I like how it takes into account the factor of engagement to depict how inspired is the audience to talk about that topic. 

1 thing that I would change/recommend to this evaluation method is that a measure for contextual completeness should be included. This could address whether the visualization includes key supporting data or contextual elements needed for informed interpretation. For eg, the chart that I have chosen, does not have contextual data regarding the population of the university. Having a rating for contextual completeness would have been useful in this situation to draw specific conclusions. 

## Step three: sketch out a solution

### Sketching solution

In my redesign of the original map, I chose to present the data in a highlight table and pie chart format to improve readability and accessibility. The table organizes universities by state, listing their loan origination amounts, which simplifies comparisons across states without the need to interpret a color-coded map. This format allows for quick reference and is especially helpful for viewers interested in specific states or institutions. The pie chart illustrates the overall distribution of loan originations across different types of institutions (public, private nonprofit, and proprietary), which makes it easy to understand the general trend—such as public universities having the most loan originations—at a glance. 

As mentioned in the critique, I think that the map didn't do enough justice to the northeastern states as those were very difficult and confusing to understand. Hence, I decided to get rid of the map entirely and instead put it all in a color coded table to make it easily readable and understandable by the users/vieweres. I also changed the color to gradients of green to make it easily distinguishable based on the originated loan amounts. Moreover, I also thought that the legend in the original data visualization was confusing as it tried to depict multiple aspect of the map (the type of institution as well as the $ in loan originations). For this reason, I decided to break the two aspects into two different graphs. The table would highlight the amount of loan origination in the university with most loan originations in each U.S state, while the pie chart would highlight the splitting by institution type to depict which type of school originates the most loan amount. The pie chart would help the policy makers make decisions easily by drawing important conlusions about which type of school originated the most loan amounts. 

![image](https://github.com/user-attachments/assets/207be031-2992-487e-8de9-bdbe348b9947)
![image](https://github.com/user-attachments/assets/69ffd849-f0f9-4409-a6d8-29eb1299b9e9)

## Step four: Test the solution

I tested my solution with 2 different users and got the following takeaways from that.

### Key Takeaways from User Feedback
- Focus only on public schools even in the highlight table because that is the most interesting story.
- Try using a tree map instead of a pie chart to make it more visually intriguing.
- Grey out the 'Private-Nonprofit' and 'Propritery' because our main focus is on Public Schools.
- Add the definition of Loan Originations as it is not a very familiar term.

## Step five: Build your solution

### Story to Tell

After addressing user feedback, I redesigned the original map into a highlight table and a tree map for improved readability.

The redesigned visualization, with a highlight table and tree map, tells a story of where student loan originations are concentrated in the U.S. Surprisingly, it’s public universities—not private nonprofits—that account for the majority of student loans, even though private schools often have higher tuition costs. The highlight table allows for quick comparisons, showing that schools like Arizona State University and Pennsylvania State University generate some of the highest loan amounts.

The tree map adds context by breaking down loan originations by institution type, with public universities taking up most of the visual space. Private nonprofit and proprietary schools are greyed out, making it easy to see that public schools are the main drivers of student debt. This focus on public institutions suggests that if we’re serious about tackling the student loan crisis, we need to start by taking a closer look at funding and loan policies for public universities, where loan burdens are heaviest.

<div class='tableauPlaceholder' id='viz1731470064345' style='position: relative'><noscript><a href='#'><img alt='Public Universities With the Most Student Loan Originations in Each U.S State (2020-2021) *Amount of Loan Originations is the dollar amount of the loans initiated during the year 2020-2021. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Hi&#47;HighlightTable_17314693328090&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='HighlightTable_17314693328090&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Hi&#47;HighlightTable_17314693328090&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
   var divElement = document.getElementById('viz1731470064345');                    
   var vizElement = divElement.getElementsByTagName('object')[0];                    
   vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
   var scriptElement = document.createElement('script');                    
   scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
   vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


<div class='tableauPlaceholder' id='viz1731469754280' style='position: relative'><noscript><a href='#'><img alt='Public Universities Have the Most Student Loan Originations  ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Tr&#47;TreeMap_17314694217960&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TreeMap_17314694217960&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Tr&#47;TreeMap_17314694217960&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
   var divElement = document.getElementById('viz1731469754280');                    
   var vizElement = divElement.getElementsByTagName('object')[0];                    
   vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
   var scriptElement = document.createElement('script');                    
   scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
   vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
