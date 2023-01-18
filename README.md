# CritterWorld

Unfortunately, the academic integrity policies at Cornell University prohibit making source code from course projects publically available. However feel free to contact me, if you find this project interesting and wish to view the source code!

CritterWorld is a project that simulates a world of small critters. These critters can move, eat, grow, attack each other and even mate with other willing critters. Critters are also able to sense the nearest piece of food with a “smell” command, implemented with a modified version of Dijkstra's shortest path algorithm.

Each critter follows a “Critter Program” that determines how the critter will behave in the world. This program is written in the “Critter Language”—a context-free grammar—defined by the course staff which can be found in the detailed project spec below. As part of the project, I wrote the parser and interpreter for this critter language. New critters created from mating of budding inherit the critter program from their parents with a slight chance of mutation—implemented using fault injection in the abstract syntax trees constructed by the interpreter of the critter language. The GUI was built in JavaFX.


more details about the project are here: https://www.cs.cornell.edu/courses/cs2112/2022fa/project/project.pdf?1668394201

images of our Critter World's UI are displayed here:

<img width="712" alt="image" src="https://user-images.githubusercontent.com/99925709/213065585-de4112f5-390b-4be8-abee-9a44f0189312.png">

<img width="1132" alt="image" src="https://user-images.githubusercontent.com/99925709/213065454-dfcf1b95-eb60-4d88-985d-2dc4f9974774.png">
