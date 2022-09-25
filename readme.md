# Godot gravity test

## Requirements

- Godot 3.5

## Setup

- a "GravityWell" Area2D which has a huge radius, large enough to ensure that the "Player" is always inside of it
- a "Player" RigidBody2D which has an initial velocity of x:0, y:100

## Results

### Expected result

I expect the Player to follow a stable orbit path which does not deviate.

### Actual result

![Godot gravity test video](/godot-gravitytest.webm)

The player follows an irregular orbit and is never stable.
