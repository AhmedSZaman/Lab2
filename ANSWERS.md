```
# 1
According to the diagram fulltime student has no methods itself. But in reality an empty class is a useless class
so at the very least it would have methods calling other classes.
``````
# 2
Part time student can only have 1 phDprogram but in that program they are able to have
anywehre from 0 to infinte thesis according to the diagram. 
PartTimeStudent has a 1 to 1 relationship to PhDProgram. Which in turn has a 0 to many relationship to PhDThessis.
``````
# 3
get rid of the Student, FullTimeStudent and PartTimeStudent classes. Aswell as getting rid of getStudent method from PhDThesis
``````
# 4
has a relationship with studnet. add attriubte void setThesis and getThesis.
```