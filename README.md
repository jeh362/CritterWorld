# CritterWorld

Unfortunately, the academic integrity policies at Cornell University prohibit making source code from course projects publically available. However feel free to contact me, if you find this project interesting and wish to view the source code!

CritterWorld is a project that simulates a world of small critters. These critters can move, eat, grow, attack each other and even mate with other willing critters. Critters are also able to sense the nearest piece of food with a “smell” command, implemented with a modified version of Dijkstra's shortest path algorithm.

Each critter follows a “Critter Program” that determines how the critter will behave in the world. This program is written in the “Critter Language”—a context-free grammar—defined by the course staff which can be found in the detailed project spec below. As part of the project, I wrote the parser and interpreter for this critter language. New critters created from mating of budding inherit the critter program from their parents with a slight chance of mutation—implemented using fault injection in the abstract syntax trees constructed by the interpreter of the critter language. The GUI was built in JavaFX.
