# Telling Stories with Data Assignment 3

**Please note: Scroll to the end of the page to view my redesign of the visual shown below.**

### Introduction

I decided to critique and redesign the visual on the following link: [Dropout Rate in India](https://data.gov.in/major-indicator/drop-out-rate)

I chose this visual because I feel that education is one of the most important factors that decide the success of a country / people in the country. Education is one of the most basic and important rights and every human has a right to education. Despite this, there is a high amount of illiteracy in a heavily populated country such as India. Redesigning this visual in a way that lawmakers can make better decisions would help the general public and citizens of India.

The initial visual is shown below:

![Img1](/Images/Img1.PNG)

![Img2](/Images/Img2.PNG)

### My critique of the visuals

In my opionion, the following things don't work / can be improved upon in this visual:
1. The visuals don't tell us what's happening on a broader level, even though the dataset does contain that information. 
2. Essentially, we have the same graph (bar chart) repeated 4 times, but in 2 different ways (column and row bar chart). This means that even though a bar chart is pretty easy to interpret, having different orientations requires some level of re-learning / re-understanding to be performed by the user which takes some time. 
3. Each graph uses a different color. A more efficient way would be to have the same color across charts and using a gradient color scheme where the higher the value, the darker the color. 
4. The gridlines also seem to be prominent, fighting for some of our attention, when it should be focused on the data/visual. 
5. The top right visual with a title that says that it shows bottom 5 states as per secondary school dropouts whereas, it actually shows primary school dropouts. 

### Wireframe of the solution

I created an initital wireframe of my solution, which was a simple pen and paper sketch, as shown below:

![Wireframe](/Images/Wireframe.jpeg)

The idea here was to show a visual that shows all india drop out rates and helps us compare easily between primary and upper primary schools. We can then see a text box with an introduction, that talks about common reasons of drop outs and states that since the all india visual doesn't show an entire visual for policy makers to decide where changes should be made, we then show a statewise comparison of primary and upper primary dropout rates from 2012-2015. 
Each dot in the statewise visuals represents the drop out rate of one state in India. And the 5 pink dots at the top depict the states with the top 5 dropout rates. 

**Upper primary schools** are schools with kids of ages 11 and 12, whereas **Primary schools** have kids with ages between 6 and 10. 

### Testing the solution

I got feedback from 2 people on my wireframe/sketch, each of which made me realize different things that I could improve with my visual:
1. User 1 indicated that it would be more useful in terms of understanding to place the textbox (originally present in the middle of the dashboard / sketch) to the top, making it one of the first things we see. 
2. Users 1 and 2 indicated that it was really difficult to understand what the 2 statewise visuals were depicting and they indicated that they would definitely change the type of visual and use something else like something similar to a bee swarm / heat map plot. 
3. User 2 also indicated that it would be helpful to see what grades exactly made up the primary and upper primary schools. 

Answers to other questions that I asked:
- Both users were able to identify that the plot was aimed towards the general public and policy makers looking to identify states where improvements could be made to the schooling. 
- Both users were able to understand the meaning of the visuals and the interpretation being derived from them. 
- User 2 thought that it might be interesting if we could show data on where the kids were coming from i.e. from rural or urban areas. That might help the viewers better understand the reasons behind dropout rates. Unfortunately, the dataset available did not have that information. 

Based on the feedback provided by the 2 users, I moved on to change my visual accordingly. 

### Building my solution

Based on the feedback received, I made the following changes:
1. I brought the text box at the top of the dashboard
2. Changed the type of visual for the statewise dropout rates to a heatmap sort of a plot, which not only puts our focus on the top values but also allows us to quickly understand the visual. 
3. I tried to maintain the color scheme through the dashboard, where the primary schools are represented by blue and and the upper primary are represented by orange. 


### Final Dashboard
My dashboard is attached below:

<iframe src="https://public.tableau.com/views/Final_16056461134900/Dashboard1?:showVizHome=no&:embed=true" width="90%" height="1200" seamless frameborder="0" scrolling="no"></iframe>

##### [Back to the Telling Stories with Data page](TSWD.md)
##### [Back to the main Portfolio page](README.md)
