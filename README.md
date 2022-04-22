# FamilyTreeProject assignment: Ancestor chart

Requirement’s specification:
A program will be designed that can be used to put together a digital ancestor diagram.
An ancestral diagram shows the ancestors of a person. The chart starts from the bottom up to two
parents, four grandparents and so on. This structure is the same for each person.

 

A directed acyclic graph is a natural data structure to model this.
It must be possible to traverse the graph through depth-first traversal.
A good solution will also have the possibility of breadth-first traversal.
A person should have at least the following attributes: First name, last name, possible year of birth, possible year of death, gender.
Add others if you feel it can enhance the use of the application.

User interface:
A user interface must be created that can be used via the command line.

As a minimum, it must be possible to:
• Add people to the graph (at least 3 layers).
• Print information about people in the graph on different if:
o Here you can demonstrate traversing, sorting, etc.

To lift the task, you should add more menu options. Some examples:
• Retrieve a selection of people based on one or more search terms.
• Modification of existing person.
Remove people in the graph.
• Storage and recovery of the data structure to / from file.
• Etc.
Users can make mistakes, and the application must take this into account and provide feedback at any time without the program crashing.
The logic does not have to be 100%. One can e.g. assume that all names are unique, which can make searching easier. Such simplifications must be documented in the code.


Device tests
The project will include unit tests that can test different parts of their code.
Automatic testing using github workflows will pull up positively and make it possible to check cross-platform compatibility.

Use of third-party libraries
You are free to use third-party libraries, but in that case use header-only libraries so that it is as easy as possible for outsiders to compile the code you write. This also applies to unit testing
framework. Catch2 demonstrated in class is header-only and can be used nicely.




• A short individual document (max. 1 page) that summarizes:
o What you have contributed, how the group has collaborated and how versioning tools and project planning tools have been used throughout the project.
o Reflect on how you have chosen to solve the project. What was the biggest challenge? What do you want to highlight that you think you have solved in a good way (what have you done to ensure high quality and a robust solution)? Based on how you have chosen to solve the project in this task, how will you evaluate your solution according to the design principles coupling, cohesion and responsibility driven design? Are there any of the classes you e.g. think could have been better designed according to the principle of cohesion? If you had more time to solve a problem, which parts of the program would you have changed (refactoring), and why?
