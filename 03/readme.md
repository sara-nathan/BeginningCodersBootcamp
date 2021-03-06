# Bootcamp 03

## Review

question time.

## new sketch 08: "map"

animate using sine and cosine, which have outputs between -1 and 1. introduce `ofGetElapsedTimef()`.

have fun with `sin(ofGetElapsedTimef())`, using map for position, colors.

## new sketch 09: "if-statement"

like the while loop, whatever goes inside the if-statement needs to sometimes be true and other times be false.

## new sketch 10: "bounce"

create the bouncing screen saver. lessons:

- using variables to modify other variables (position-velocity)
- use if-statements to detect an *out of bounds* state, and respond accordingly.

this introduces our first big problem on *code design*. many different variables conceptually relate to the same thing. how might we combine these variables in code as well?

## new sketch 11: "particle"

re-code our bounce object but into a custom particle class.

expand it by creating an **array of particles**. (this gets really fun when you add gravity!) demonstrate a fireworks sketch.

## video content: "returning"

functions that return. transform a number `b = transform(a)`.

## video content: "for-loop-2"

extend our previous for-loop-1 sketch into 2D, we want a color grid now, using nested for-loops.

make a sketch that draws colored rectangles in rows and columns, iterating through 2 colors. use map.

## Homework

play with `sin` and `ofGetElapsedTimef`, try them in a loop, with the `i` modifying each instance.
