# A column generation example in Julia & JuMP

Going through the cutting stock problem, we define the master
and sub-problem and solve a linear relaxation with column generation,
and then branch on the generated columns to find an integer solution.

## Requirements

Running the column generation notebook just requires JSON, JuMP, Clp and Cbc.
You can easily replace these with any LP + MILP solver.  

To generate random instances of the problem, you can change the seed in the 
*build_data.ipynb* notebook and save the resulting problem to `data.json`.

## Further reading

The ideas for this notebook rely on:
* The [JuMP example](http://www.juliaopt.org/notebooks/Shuvomoy%20-%20Column%20generation.html)
* Lecture on Integer Programming, G. Desaulniers, Polytechnique Montréal
