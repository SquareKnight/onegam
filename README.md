# GraphMaph

GraphMaph aspires to be a graphical interface for solving math problems and puzzles. Its intended use is focused on tackling the problems at [ProjectEuler.Net](https://projecteuler.net/)

The design is done in a pipeline-construction, where an input is transported to transformations, and the result is again transported to transformations, etc, until a satisfactory outout is reached.

## Pipes

By default, a pipe just transfers one value from one component (input or transformation) to another component (transform or output). Several default operations for transport are available, ie sending the same value to multiple components, for-each, conditional split etc. Also, you can define custom actions in the transport pipes.

## Transformations

Transformations take inputs, transform them in some fashion and return an output. Think of calculating prime factors, taking an average, simple summing of inputs, GCD etc. A lot of these will be available as standard transforms, and there will be room for custom editing of these.
