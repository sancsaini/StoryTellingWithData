## Homework 3 - Women Representation by Party (in US House of Representatives)
### Original visualization
The original visualization was from a [tweet](https://twitter.com/Spelk24/status/1049054474411675658) by a student who was performing exploratory data analysis on data present in a report by Congressional Research Service [linked here](https://fas.org/sgp/crs/misc/RL30261.pdf), which found its way onto the [Makeover Monday website](http://www.makeovermonday.co.uk/data/data-sets-2018/) which encourages people to experiment with data visualizations.
![](https://pbs.twimg.com/media/Do79etiUcAA9IgS.jpg)


### Changes to the visualization
While the visualization is a very beautiful one to begin with, it has eliminated some information that may add to a reader's understanding:
* additional labels for some of the prior years to give numbers for prior years
* an indication for what the maximum percentage representation for a particular party was and when it happened
To this end, I made the following wireframe:
![](https://raw.githubusercontent.com/sancsaini/StoryTellingWithData/master/Wireframe.JPG)

### Feedback on the wireframe
I tested the solution with two Indian students (1 male, 1 female) from the Information Systems program and asked them open-ended questions w.r.t to the wireframe. They:
* Surprisingly could figure out that the blue color signified Democrats and red color signified Republicans
* __Didn't understand what the y-axis representated__. So they faced difficulty in figuring what the maximum lines for respective parties represented (*Action*: Added a y-axis label and title to the final viz)
* One of them highlighted that the scale of the viz seems messed up as it seems to __overinflate the representation amongst Democrats__, even though the two parties should be aiming for an equal representation at least. At the same time, the other person mentioned that it was __weird for a percentage chart to not have 100% scale__. (*Action:* Scaled up the visualization to 100% scale and added two reference lines corresponding to 50% and 100% representations respectively)
* One of them wondered about the __font color of labels__ (*Action:* Used party color for labels on a particular party's line as well as maximum representation line)
* Overall, both the users got a sense of what the visualization was conveying.

### Final visualization:
While incorporating the feedback, I also decided to include the source of data with the title, and decided to include an x-axis title which serves as a disclaimer that the points are plotted at the Congress session's start year. The original visualization's stepped representation managed to avoid this problem altogether.
![](https://raw.githubusercontent.com/sancsaini/StoryTellingWithData/master/Final%20viz%20-%20Women%20Representation%20by%20Party.png)
