In this project we set out to address three principal questions about grade distributions at UW-Madison:
1) do students generally perform better in classes in one foreign language than others?
2) does the room in which a class is taught have any relationship with grades awarded to that class?
3) does time at which a class is taught have any bearing on grades awarded to that class?

The database we used to answer these questions can be found here:
https://www.kaggle.com/Madgrades/uw-madison-courses

The code we used to address these questions is in the Jupyter notebook titled 'Mod03_everybody'

To address the first question, we calculated the proportion of students who passed each class as well as the proportion of students who earned a B or better in each class. We then performed a Kruskal-Wallis test to compare the proportion of students that pass classes in each foreign language as well as a Kruskal-Wallis test to compare the proportion students that earn a B or better in each foreign language. We found that a smaller proportion of students pass Portuguese than classes in other languages. We also found that a smaller proportion of students earn a B or higher in Spanish and Portuguese classes, while a larger proportion of students earn a B or higher in German and Asian language classes.

To address the second question, we identified specific courses that were taught by the same set of instructors in two different classrooms.  We performed a two-sided independent t-test to compare the proportion of A's awarded to students who took the class under the same instructor in two different rooms.  We found a significant difference in the proportion of A's were awarded in certain rooms relative to others - but further work may need to be done to isolate this effect to the classroom such as controlling for time of day or year.

In order to address the third question, we performed a z-test to compare the pass rate for all classes taught at 8 AM to that of all classes taught at 1 PM.  We failed to find a difference in the pass rate between classes taught at 8 AM versus classes taught at 1 PM.

In sum, we conclude that while there is no difference in proportion of students who pass at 1 PM or 8 AM, students may perform differently in the same course depending on the room the course is taught in.  Pass rates across foreign languages are relatively similar (with the excpetion of Portuguese), but more students earn A's and B's in German and Asian language classes than in other foreign languages.


