# Mathematica-FractalTree

## Project
This project was created for my Multivariable Calculus course in senior year in highschool (2016) as a culmination of learning Mathematica. The prompt was to simply create an interesting 3D graphic using Mathematica.

## Idea: Generated Trees with Fractal Structures
This is obviously not an entirely original idea. I was brainstorming for ideas when I remembered this simple, yet interesting programming exercise: generation of trees with fractal structures.
One quick google search led me to images such as this:

![Fractal Tree from Google Image Search](http://i.stack.imgur.com/6w23I.png)

From here I took this idea and set out to create a 3-Dimensional version of it using cylinders as my basis for branches.

While the algorithm for the generation most likely has been implemented in a similar way before, I did not use any external sources besides an image reference to come up with the code for this project.

## Sample Outputs

![Sample 1](http://i.imgur.com/8sxYhsS.png)

![Sample 2](http://i.imgur.com/e79WWu6.png)

## Conclusions
I am pretty satisfied as to how this turned out. I feel like I learned a lot in the process and definitely got a feel around the procedural programming aspects of Mathematica. I also realized that I don't like them and find them unintuitive relative to other programming languages. However, I can't be too critical as it was designed as a functional programming language.

## Further Exploration
One thing that I did not have the time to do, that I thought would have been fun, is to divert slightly from the fractal idea and instead generate the tree structure using pseudo-random functions provided by Mathematica.

The idea would be to have some percentage chance that you would branch at a certain depth. (This would also allow for more wild trees to be generated depending on how the percentage cut-off dips off).

From there you would also randomize the angles at which the branches would divert. This, given vetted parameters, would most likely produce much more organic looking trees than the ones that I generated.

Another idea is to simply generate the branches in more angles other than only diverting about the Y-Axis. I decided not to do this because I wasn't sure about how many objects I could generate before Mathematica's memory buffers were filled. But it could be an interesting idea to explore.
