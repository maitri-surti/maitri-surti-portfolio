| [Home Page](https://maitri-surti.github.io/maitri-surti-portfolio/) | [Visualizing Government Debt](https://maitri-surti.github.io/maitri-surti-portfolio/dataviz2) | [MakeOverMonday](https://maitri-surti.github.io/maitri-surti-portfolio/makeOverMonday) |

# Assignment: Critique by Design with Tableau (MakeoverMonday)

## Step one: choose a data visualization from MakeoverMonday
[Data Viz Link](https://howmuch.net/articles/university-with-the-most-student-loan-originations-in-every-state)

![image](https://github.com/user-attachments/assets/896cf5e2-3306-4fdf-834f-f0b2731b7b6f)

### What the data visualization shows
This visualization shows the universities in each U.S. state with the highest student loan originations for the 2020-2021 academic year, illustrating both the total loan amounts and institution types. Using color-coding, it distinguishes between public, private nonprofit, and proprietary institutions, with darker shades indicating higher loan amounts. The map reveals notable patterns, such as Arizona State University ($568M) and Liberty University ($447M) having some of the highest student debt burdens. This data viz allows for quick comparisons across U.S states and highlights the financial challenges faced by students at different types of institutions across the country.

### Motivation to choose this data viz
As an international student, I found this visualization especially relevant and insightful, given my own experience navigating educational financing. Coming from abroad, I was eager to understand the student loan landscape in the U.S., where college debt is a significant factor for many students. This map helps me appreciate the scale of loan originations across different institutions, showing where student debt burdens are highest. Having gone through a similar process to finance my own studies, I can empathize with the financial pressures U.S. students face and see how these trends vary by institution and region. This visual highlights not only the importance of financial planning for higher education but also deepens my understanding of the financial commitments many of my peers have made to pursue their academic goals.

## Step two: critique the data visualization

### My critique about the data viz
Overall, what worked well is that the data viz has taken into account only one university per state which has the highest student loan origination in each U.S. state. This avoids cluster around the map and helps user draw conclusions of only the most important aspect rather than showcasing all the universities in that state. However, according to me what didn't work very well was the legend based on the type of university (public, private-non profit, proprietary). I think the legend is confusing for the users to understand. I also think that the data viz is not taking into account the population of a university to draw accurate conclusions. If I were to do something different, I would improve the legend for the segregation based on the type of university and maybe remove the university logo from each state as that is making the map look super clustered. Also, the northeaster states look very clustered and difficult to read.  Moreover, the 3 universities at the bottom right do not clearly state the location that they belong to, it looks like those are just randomly included (I had to google those universities to look for their location). For example, for the legend, I would probably have 3 different colors for the university types and have a stroke on each university with that color. 

### Primary audience for the visualization
Education policy makers and government officials are the primary audience for this tool. For the primary audience, the data viz is fairly effective due to 2 main reasons:
1. By showing which universities generate the most student loan debt in each state, this visualization helps policy makers quickly identify institutions where debt burdens are highest. 
2. The color-coding by institution type (public, private-nonprofit, proprietary) provides a useful breakdown, allowing policy makers to assess whether certain types of institutions contribute more to student debt.
   
### Evaluating Stephen Few’s “Data Visualization Effectiveness Profile”
Evaluating the data visualization using Stephen Few’s “Data Visualization Effectiveness Profile” offers a structured, detailed approach for examining its strengths and areas for improvement, particularly regarding usefulness (8/10), completeness (6/10), perceptibility (5/10), truthfulness (7/10), intuitiveness (5/10), aesthetics (3/10), and engagement (6/10). I feel that it mostly covers all the necessary elements that would be useful in examining a data viz. I like how it takes into account the factor of engagement to depict how inspired is the audience to talk about that topic. 

1 thing that I would change/recommend to this evaluation method is that a measure for contextual completeness should be included. This could address whether the visualization includes key supporting data or contextual elements needed for informed interpretation. For eg, the chart that I have chosen, does not have contextual data regarding the population of the university. Having a rating for contextual completeness would have been useful in this situation to draw specific conclusions. 

## Step three: sketch out a solution

### Sketching solution

In my redesign of the original map, I chose to present the data in a table and pie chart format to improve readability and accessibility. The table organizes universities by state, listing their loan origination amounts, which simplifies comparisons across states without the need to interpret a color-coded map. This format allows for quick reference and is especially helpful for viewers interested in specific states or institutions. The pie chart illustrates the overall distribution of loan originations across different types of institutions (public, private nonprofit, and proprietary), which makes it easy to understand the general trend—such as public universities having the most loan originations—at a glance. 

As mentioned in the critique, I think that the map didn't do enough justice to the northeastern states as those were very difficult and confusing to understand. Hence, I decided to get rid of the map entirely and instead put it all in a color coded table to make it easily readable and understandable by the users/vieweres. I also changed the color to gradients of green to make it easily distinguishable based on the originated loan amounts. Moreover, I also thought that the legend in the original data visualization was confusing as it tried to depict multiple aspect of the map (the type of institution as well as the $ in loan originations). For this reason, I decided to break the two aspects into two different graphs. The table would highlight the amount of loan origination in the university with most loan originations in each U.S state, while the pie chart would highlight the splitting by institution type to depict which type of school originates the most loan amount. The pie chart would help the policy makers make decisions easily by drawing important conlusions about which type of school originated the most loan amounts. 

![image](https://github.com/user-attachments/assets/207be031-2992-487e-8de9-bdbe348b9947)
![image](https://github.com/user-attachments/assets/69ffd849-f0f9-4409-a6d8-29eb1299b9e9)

## Step four: Test the solution

### User 1 feedback (student, mid 20's)
While testing both of my sketches with the user, I noticed that they faced some difficulty in recognizing what exactly "Loan Originations" mean with respect to the visualization. To take this feedback into account, I would add an asterisk on the word "Loan Originations" and mention the exact definition as the end of the table for better clarity. One thing they found surprising is that public schools have the highest loan originations. They hadn't expected this because public schools are usually cheaper than private schools. To this, I had to clarify that this data viz does not take into account the population of the school. Since, public schools often tend to have a greater population of students, they have the highest loan originations. 

### User 2 feedback

