# A column generation example in Julia & JuMP

Going through the cutting stock problem, we define the master
and sub-problem and solve a linear relaxation with column generation,
and then branch on the generated columns to find an integer solution.

## Requirements

All requirements are defined in the Project.toml, just activate and
instantiate the project.

## Further reading

The ideas for this notebook rely on:
* The [JuMP example](http://www.juliaopt.org/notebooks/Shuvomoy%20-%20Column%20generation.html)
* Lecture on Integer Programming, G. Desaulniers, Polytechnique Montréal
