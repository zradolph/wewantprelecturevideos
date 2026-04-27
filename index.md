---
# Do not edit the text between these lines!
layout: default
---
# The Idea:

We took the combined survey data from the COMP 110 class surveys and analyzed how much people wanted pre-lecture videos and livestreams of lectures, and also looked to see how this differed by sub-group or correlated with other aspects of respondents. In the end, we wanted to see just how much evidence there was to support adding pre-lecture videos and livestreams, with a particular focus on pre-lecture videos!

## Livestream Support by Class

We first split up all the responses by their class status (Freshman, Sophomore, etc.) and found the proportion of them who supported a livestream of lectures. For this, we included only those who picked 5-7 on the scale of support. 

<img src="zradolph.github.io/wewantprelecturevideos/static/imgs/class.png" alt="Bar graph containing the proportions of each class that supports adding livestreams. Junior, Sophomore, and Senior are high, while Freshmen and Graduates are slightly lower." width="500"/>

We were surprised at first to see Freshmen at the lowest support, but it makes sense since most of them come to class, something upperclassmen do less. However, even with Freshmen at the lowest support, they still had above 60% support for the idea, proving it is popular among all classes.

## Pre-Lecture Video Support among Freshmen based on prior coding experience

Here, we only took the data of Freshmen and split them up based on their prior coding experience- whether they had any or not. We then took the proportion of those who supported adding pre-lecture videos and compared them.

<img src="zradolph.github.io/wewantprelecturevideos/static/imgs/experience.png" alt="Bar graph containing the proportions of freshmen based on prior experience that supported adding pre-lecture videos. Those with experience had higher rates of support than those who did not." width="500"/>

We were surprised once again, seeing that those with prior experience had higher rates of support for pre-lecture videos. However, both groups had a higher than 65% support for adding them, showing that there is a strong support among freshmen for the addition of pre-lecture videos.

## Pre-Lecture Video Support based on Level of Understanding

We pivoted here to looking at if there was an association between pre-lecture video support and level of understanding. Of course, we cannot do mathematical procedures, but we could use the eye test.

We had to do some complicated looping to create a table with the number of times each value showed up in the dataset, but we eventually succeeded and were able to visualize it in a scatter plot.

<img src="zradolph.github.io/wewantprelecturevideos/static/imgs/understanding.png" alt="Scatter plot containing the amount of responses for each level of pre-lecture videos (on the x-axis) and understanding (on the y-axis). There is a high concentration of these responses in the middle level of understanding and high level of support for pre-lecture videos." width="500"/>

We see a large cluster of responses with high support for pre-lecture videos and middling understanding, indicating that this group of students, who have varying degrees of understanding, generally have high support for pre-lecture videos.

## Office Hour Visits and Support for Pre-Lecture Videos

Our final analysis looked at if there was an association between office hour visits and pre-lecture video support. We made a new table with office hour visit amount and reused much of our code for the previous analysis to create our results.

<img src="zradolph.github.io/wewantprelecturevideos/static/imgs/office hours.png" alt="Scatter plot containing the amount of responses for each level of support for pre-lecture videos (on the x-axis) and the number of office hours visits per assignment (on the y-axis). There is a high concentration of data for those with high support for pre-lecture videos and those who visited office hours little to never." width="500"/>

This graph did not tell us much besides that there is a high degree of support for pre-lecture videos, but it does show that even though there are people who attended office hours often, they still had support for pre-lecture videos, as the size and color of the dots get bigger as the graph moves right. Essentially, people strongly support adding pre-lecture videos.

# Conclusion

The data recommends that COMP 110 professors should post pre-lecture videos and, to a lesser extent, livestream lectures to be put on the course website. This would increase accessibility for students and also give more sources to increase understanding.

In our research, we discovered that a majority of students of all academic statuses supported an option for livestreaming. We were surprised to learn that freshmen had the lowest level of support for the idea, but still, 60% of them supported it. Furthermore, we discovered that a large number of freshmen in particular, whether they had experience or not, supported the idea of pre-lecture videos to allow for pre-study. The fact that more freshmen with experience supported it than those who didn't was also surprising, but the results don't lie: over 65% of both groups supported the idea.

We also discovered that most students, regardless of understanding, had a high support for the idea of pre-lecture videos, with a high amount of people with middling understanding supporting it heavily. Beyond that, we also found that pre-lecture videos were heavily supported regardless of the amount of times office hours were visited, with both those who attended no office hours and those who attended highly often having support for pre-lecture videos. As such, we believe it is a good idea to implement pre-lecture videos, and based on our previous evidence, livestreaming is also quite popular.

This will, of course, have some ramifications. Firstly, regarding livestreams: the cost of recording them is not difficult, but there are concerns with storage space needed to hold lecture videos as well as reasonable fears that there will be a decrease in in-person attendance. These concerns are reasonable, but we think that, in the interest of accessibility, it is worth this cost. Plus, it is not like attendance is especially high as is.

Secondly, regarding pre-lecture videos: This is extra work that will likely fall to either TAs or to the instructor of the course- whoever is updating the course websites. This adds on to an already high workload for the instructors and TAs, as COMP 110 is certainly not an easy class to manage, and adding another agenda item to the daily list of tasks is certainly going to take a toll. There is also no way to tell if it would even be used, because despite a majority of people supporting the idea, there is no way to determine whether people will view the videos unless they are made mandatory, which would most likely result in a decrease in support for the idea. But there is an argument to be made that if it helps even one person increase their understanding, then it is worth it. Plus, there is a very real possibility that it may also result in fewer tutoring sessions being required, which is another benefit.

Of course, the throughline to all this is that the time and effort required on the part of instructors and TAs would increase, while there is no guarantee that students will even take advantage of the resources. However, in our opinion, this would be worth doing if instructors and TAs wish to listen to student feedback and provide as many resources as possible.

One way this idea could be extended would be looking at what specific areas the pre-lecture videos should focus on. One way we think this could be done would be adding a question on future surveys asking which parts of the class were the most difficult to understand, with options such as memory diagrams, syntax, programming concepts, etc. And then, after looking at the results of that data, choices can be made on what specific things the pre-lecture videos should emphasize. This way, the maximum understanding can be obtained from these pre-lecture videos. This is just one idea, there likely are many other approaches that can be taken, such as student feedback in class, or looking at test results. Any data source that can indicate where students need the most help should be utilized to optimize the topics covered in these pre-lecture videos.