# Embodied Code Documentation

<img src="https://user-images.githubusercontent.com/1598545/158480305-1e9010cf-8dc9-4a37-a34a-b15a1ad84521.png" width=400>

Follow our [Getting started with Embodied Code on the Quest 2 headset](./getting-started.md) tutorial to install the app on our headset and run the first tutorial. 

# Reference

## Extrude Tool

![xrdesign embodiedcode-20221109-225253](https://user-images.githubusercontent.com/82526625/201984396-093217fc-e282-417a-ac36-a64db2f174b7.jpg)

[Documentation for the Extrude tool](./extrude-tool.md)


# Example Scenes

## Gesture

Demonstrates creating a gesture in space, and using that as a signal to drive the motion of a game object.

<img src="images/gesture01.jpg" width=400> <img src="images/gesture02.jpg" width=400>

To load the scene: `load ex_gesture`

## Gravity

Game objects move upwards (low gravity) until they encounter a height threshold, and when they fall with high gravity.

<img src="images/gravity01.jpg" width=400> <img src="images/gravity02.jpg" width=400>

To load the scene: `load ex_gravity`

## Gravity Box

Define lower gravity within a box. When objects hit the bounds of the box, normal gravity is restored.

<img src="images/gravbox01.jpg" width=400>

To load the scene: `load ex_gravbox`

## Popcorn

Create a pile of game objects. Set a timer which periodically launches one of those objects with a random upwards velocity. ("pop!")

<img src="images/popcorn01.jpg" width=400>

To load the scene: `load ex_popcorn`

## Tower of Cubes

Use sliders to create a wall of cubes (_n_ cubes, in _m_ columns). Random forces ("wind") or user ineraction cause the objects to topple.

<img src="images/tower01.jpg" width=400>

To load the scene: `load ex_tower`

## Drone

Inside of a 3d modeled corridor, gestures define two possible paths for a drone. Send the drone to navigate the hallway.

<img src="images/drone01.jpg" width=400> <img src="images/drone02.jpg" width=400>

To load the scene: `load ex_drone`

# Coding Challenges
- [coming soon]
