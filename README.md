# wind_over_water.jl
A study of the atmospheric boundary layer over the ocean

## Log

- [__Notebook 1__](https://github.com/robot144/wind_over_water.jl/blob/main/wind_profile_01.ipynb): First test with a log-profile. The turbulence closure uses the simple algebraic model $\nu=\kappa u_{*} z$.

## More info

The code in this repo relies heavilly on existing packages. Please, consider their documentation
- [SciML](https://docs.sciml.ai/Overview/stable/) Aims at Scientific Machine Learning but is also an excellent reference for solving differential equations in Julia
- [Juliacon 2018 talk on by Chris Rackauckas PDEs](https://www.youtube.com/watch?v=okGybBmihOE) Gives a good overview of how packages can specialize and work together for solving PDEs.
- [DifferentialEquations.jl](https://docs.sciml.ai/DiffEqDocs/stable/getting_started/) Package for time-integration of differential equations.
