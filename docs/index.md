
# Example page for using Weave.jl with Jekyll



````julia
using Plots
pyplot()
x = linspace(0, 2π, 1024)
plot(x, sinc(x))
````


![](figures/index_1_1.svg)
