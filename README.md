# Go: Robot Simulator

Write a robot simulator.

A robot factory's test facility needs a program to verify robot movements.

The robots have three possible movements:

- turn right
- turn left
- advance

Robots are placed on a hypothetical infinite grid, facing a particular
direction (north, east, south, or west) at a set of {x,y} coordinates,
e.g., {3,8}, with coordinates increasing to the north and east.

The robot then receives a number of instructions, at which point the
testing facility verifies the robot's new position, and in which
direction it is pointing.

- The letter-string "RAALAL" means:
  - Turn right
  - Advance twice
  - Turn left
  - Advance once
  - Turn left yet again
- Say a robot starts at {7, 3} facing north. Then running this stream
  of instructions should leave it at {9, 4} facing west.

The tests are written using the `testing` package in the standard library.

To run a test file use the `go test` command:

    go test

## Source

Inspired by an interview question at a famous company.

This exercise is from the [Go][go] track on [Exercism][exercism]

[exercism]: http://exercism.io
[go]: http://exercism.io/languages/go



