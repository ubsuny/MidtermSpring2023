# Computational Physics Midterm Spring 2023

![Video_Game_Cover_-_The_Last_of_Us.jpg](attachment:Video_Game_Cover_-_The_Last_of_Us.jpg)


Suppose you have a pandemic of cordyceps fungal infection as in the game and show "The Last of Us". If someone is infected by the cordyceps fungus, they become a zombie who feeds on other people, and infects them, creating more zombies. There is a single person, Ellie Williams, who is immune to cordyceps infection. If you are a fan of the show, we will be diverging from canon now. Suppose that a group of people (the "Fireflies") has benignly developed a **cure** for cordyceps, but not a **vaccine**, using Ellie's blood. If the treatment is administered, the person in question is no longer infected. However, they can be re-infected by being bitten again. This means Ellie herself is the best person to administer the vaccine, so she will be wandering around aimlessly administering the vaccine to nearby people. She has an infinite supply of vaccine.  


We will consider `n_walker` random walkers in 2 dimensions that each take `n_steps` steps. At each step, the walkers can move `d` units in either x or y. The walkers are confined to a single 1x1 room with cyclic boundary conditions in x and y (so, the walkers wrap around if they wander off the edge). There is a configurable initial number of infected zombies, `n_infected`.  There is always one person immune (Ellie), but healthy people can be infected by zombies and cured by Ellie. 

The code below assumes that there is zero rate of transmission from the infected individuals (i.e., passive zombies). The animation shows the paths of the walkers. The healthy individuals show up as blue dots. The zombies show up as red dots. Ellie is a green dot.
