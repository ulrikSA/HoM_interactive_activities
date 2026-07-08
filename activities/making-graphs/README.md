# Making Graphs: Write It From Scratch

## Concept
Students practice writing the equation of a quadratic function from its graph.

## Student Interaction
The student looks at a parabola on a coordinate grid and types the full function in the form `y = ...`.

## Correct Behavior
The activity draws the student’s curve and checks whether it matches the target graph.

Target function:
`y = -2(x - 2)^2 + 4`

The correct graph:
- Opens downward
- Has vertex `(2, 4)`
- Has the correct width/steepness

## Wrong Behavior
If the answer is wrong, the activity gives specific feedback:
- Wrong sign: curve opens the wrong way
- Wrong x-position: vertex is too far left/right
- Wrong y-position: vertex height is incorrect
- Wrong coefficient: curve is too wide or too narrow

## Variables
- Target function
- Vertex position
- Opening direction
- Width/coefficient
- Grid range
- Feedback messages

## Prototype
Claude Design link: https://claude.ai/design/p/42a4ad78-8a77-43a3-b5a8-a8789f9b0b1d?file=Activity3.dc.html&via=share

## Developer Notes
This activity should compare the student’s typed function against the target graph by checking:
- Opening direction
- Vertex x-value
- Vertex y-value
- Width/steepness near the vertex

The current prototype uses animated graph drawing and feedback after submission.
