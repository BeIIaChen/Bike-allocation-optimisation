# Bike-allocation-optimisation

# Problem description
Analyze the bicycle sharing system of a theme park (SWS Theme Park), which is a closed system, meaning bicycles can only be used within the park, with docks for the bicycles. See if the current system is feasible and if not, propose improvements.

The SWS Theme Park has four attractions, each of which has a bicycle station (the attractions and the corresponding stations are represented as A, B, C and D respectively.

Each station has a collection of bicycles and docks. The number of bicycles at each station is 80. Initially, the number of docks is the same as the number of bicycles.

Tourists can rent bicycles only if there are bicycles available at the station and can return bicycles only if there are empty docks at the station. When there are no bicycles at the station, tourists who want to rent bicycles need to wait for the bicycles, on a first-come-first-serve basis.

Tourists can start their journey at any attraction, i.e.  they arrive at random at any of the four attractions, and we assume they will visit at least two attractions before leaving. It is 2 kilometres between A and B, 2.5 kilometres between B and C, 3 kilometres between C and D, and 1 kilometre between D and A. As shown in the figure, the road is one-way and is wide enough for tourists to travel. Tourists have to ride bicycles to get from one attraction to another.

After arriving at one attraction, a tourist will spend some time visiting the attraction.  They need to return their bikes to the station at that attraction prior to visiting it.  If they want to go to the next attraction, they will need to queue to rent bicycles again

## Cost considerations
To devise cost-effective solutions, you may wish to consider the following costs:
-	Redistributing number of bicycles or docks: Negligible (done by own staff)
-	Adding more bicycles: $80/bicycle
-	Adding more docks: $100/dock


# Results
By running simulations, we found out that the optimal bundle the theme park should go with is:

For the condition of equal bikes and docks at each station: 
Bikes: 40, Docks: 105 for each station.
<img width="644" height="131" alt="image" src="https://github.com/user-attachments/assets/2d3397b9-0faa-4d9b-a3e0-5455995293b3" />


If allowed tailored plan for each attraction: 
A: Bikes: 49 Docks: 68
B: Bikes: 23 Docks:97
C: Bikes:46 Docks:65
D: Bikes:27 Docks:88

This give arise to a cost of 43,400 singaporian dollars, acheiving a tourist satisfaction rate of 81%
<img width="797" height="150" alt="image" src="https://github.com/user-attachments/assets/638a674c-ecfa-4148-98c8-285bf6856f54" />



