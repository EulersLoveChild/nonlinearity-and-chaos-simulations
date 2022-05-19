# Nonlinearity and Chaos Simulations

Below, I document some physics simulations that fall under classical mechanics, but are nonlinear and delve into chaos. This was done using Newtonian, Lagrangian, and Hamiltonian mechanics. These scenarios are based off of the problems from 'Classical Mechanics' by John R. Taylor.

- The angles were measured from the vertical down.

- Each simulation below (except N-Body) has two plots: y vs x and x vs t. The former is more visual and shows (and updates) the positions of each object along with side objects (which are taken to be massless), like springs and strings. The latter plot shows how the position changes (of objects with mass) with respect to time and is a simple scatterplot.

- In the formor plots, strings are always black. Objects with mass are any color but those. The transparent circles of these graphs are the initial position of each of the objects with mass and are given just as a way to visually compare intial vs final positions of the system.

- In the latter plots, the colors of the objects with mass are the same as their colors from the first plot. 

* **The gif and picture are from clearly different runs of the experiments**

## Driven Damped Pendulum (2-D)

I separate the simulations into three categories, based off of the values of the drive strength (γ).

### Period One (γ < 0.8)

In this simulation, the pendulum starts off with a very chaotic path, but the transiets die down and settles into a sinusodial path.  

### Period Two (0.8 < γ < 1)

In this simulation, one can clearly tell that the pendulum still has a very sinusodial path, due to its weight being larger than the driving force. 

### Period Three (γ > 1)

![](https://media.giphy.com/media/b1BmyzNBOvzX0XHIK3/giphy.gif)
![](https://i.imgur.com/MCXmkwF.png)

In this simulation, the transients are too dominant and make the pendulum chaotic for a long time.