# Canvas Sketch Project: Connected bouncing dots
This project is a simple simulation of moving agents on a canvas. It uses the canvas-sketch library for the sketching environment.

[See it live](https://codesandbox.io/s/bouncing-dots-zjy8s7?file=/src/index.js)

## Installation
Before running the project, you need to install the necessary dependencies. Run the following command in your terminal:

### npm install

## Running the Project
To run the project, use the following command:

```bash
npx canvas-sketch index.js --open
```

This will start the canvas-sketch tool and open your default web browser with the sketch.

## Description of the Simulation
The simulation creates a number of agents that move around the canvas. Each agent is represented as a circle, and lines are drawn between agents that are close to each other. The agents bounce off the edges of the canvas.

- const sketch is a function that sets up the sketch. It creates the agents and defines how they should be updated and drawn for each frame of the animation.

- class Vector is a simple 2D vector class used for the position and velocity of the agents. It includes a method getDistance to calculate the distance between two vectors.

- class Agent represents an agent in the simulation. Each agent has a position (pos), velocity (vel), and radius. The bounce method makes the agent bounce off the edges of the canvas. The update method updates the agent's position based on its velocity. The draw method draws the agent on the canvas.

## Customization
You can customize the simulation by changing the parameters in the index.js file. For example, you can change the number of agents, their speed, their size, and the distance at which lines are drawn between them.