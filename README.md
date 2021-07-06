
<p align="center"><img width=12.5% src="https://github.com/alridha/travelling-pirate-man/blob/master/images/circle_pirate.png"></p>
<p align="center"><img width=60% src="https://github.com/alridha/travelling-pirate-man/blob/master/images/Pirate_Adventures.png"></p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)

<br>

## TODO list

- [x] Adding Longest Increasing Subsequnce as solution to the ![formula](https://render.githubusercontent.com/render/math?math=M) constraint
- [ ] Fixing the broken code logic of 2-OPT swapping implementation, doing iterative local search correctly
- [ ] Try to implement new algorithms like the [Domino Algorithm]:https://iopscience.iop.org/article/10.1088/1757-899X/528/1/012043/pdf
- [ ] Using Dynamic Programing and getting rid of all redundant repeated calculations
- [ ] Making this code faster by using Cython and calling some Minizinc functions
- [ ] Rewrite the entire work in C++ providing additional version of the project
- [ ] Embedding into Tkinter GUI, and making an executable as a finished product.
- [ ] Using Minecraft to visualize Island selection and the Pirate's tour

### Epsiode One
Captin Mich is a renown pirate, nurturing a plan to rob several islands in the Carbian Sea(total of ![formula](https://render.githubusercontent.com/render/math?math=n) islands). He knows how much money he can capture on each island(thanks to Panama Papers he has in the ship library),
as well as he knows the coordinates of all the islands(as there is a stolen cell phone with Google Maps in the pirate's possession). Captin Mich wants to visit some of the islands that are shown on the Google Maps,
starting from his homeisland and finishing his journey there as well. Captin Mich knows that sailing is not cheap:
to go some distance ![formula](https://render.githubusercontent.com/render/math?math=d) by sea requires the amount of money that is numerically equal to ![formula](https://render.githubusercontent.com/render/math?math=p*d).
During his voyage Captin Mich wants to get as much total profit as possible, so he would agree to not visiting any island if the cost of going there outweighs the money stored on that island, the only exception is the pirate's homeisland.
there is one important restriction: the total amount of money that Captin Mich captures on any ![formula](https://render.githubusercontent.com/render/math?math=k) consecutive island must not exceed ![formula](https://render.githubusercontent.com/render/math?math=M), or the captin would be overflowed with his pirates glory and would overdose rum, while celebrating the victories.

Now, who else Captin Mich would ask to help planning the voyage, if not the Tech scouts!

## Visualize the tour
<p align="center"><img width=95% src="https://github.com/alridha/travelling-pirate-man/blob/master/images/long_tour.png"></p>

<br>

### Episode Two
Captin Mich is celebrating; using the money he got from the previous affair, he was able to upgrade his ship to a 4x4 mode, but it now requires more fuel and now more expensive for the Captin to sail(so the parameter ![formula](https://render.githubusercontent.com/render/math?math=p) got higher). As more money is needed to pay travel expenses, less money is left for partying, and Captin is no more afraid of overdosing rum, so ![formula](https://render.githubusercontent.com/render/math?math=M) got much larger.
Provide the Captin with the best route through islands now.


### Episode Three (Basic Euclidan TSP)
Captin Mich sold his ship and now travels by Seabus. Although less comfortable, it get much cheaper! The rules on board of Seabus forbid partying, so the Captin will not consider ![formula](https://render.githubusercontent.com/render/math?math=M).
Help the captin find the best route through the islands now.
<p align="center"><img width=90% src="https://github.com/updowntree/Mich_the_pirate/blob/master/images/ETSP.png"></p>

### Episode Four (Vertex cover)
The Captin wanted to pick the islands that allows him to for an Archipelago for entourage, so that they can an eye on the Pirate's kingdom of stolen islands,
Help the Captin to find the minimal number of islands to form that Archipelago that covers the whole empire.

### Episode Five (Bin Packing)
The Captin wanted to take as less containers as possible on his chip in order to not have any problems caused by redundant weight and volume, while he can still be sure, that he can fit all the spoils from his invasions into the containers that he has already taken, Help the Captin fitting the spoils and the items chosing the containers that fits most with his journey.


<br>
