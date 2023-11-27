My graduate astrodynamics coursework introduced computation as a means
for physical discovery. For my final term project, I replicated halo
orbit and invariant manifold solver implementations, as summarized by
Megan Rund's [thesis](https://digitalcommons.calpoly.edu/theses/1853/)
on low-cost interplanetary transfer techniques. Multiple differential
correction flavors are documented in literature, but I found no
published guidance for algorithm selection. My final paper presented a
decision tree which maps desired orbit characteristics to compatible
flavors of differential correction, several open source Julia
[packages](https://github.com/cadojo/GeneralAstrodynamics.jl), and over
130k [initial
conditions](https://github.com/cadojo/CR3BP-Manifold-Research) for
periodic orbits.
