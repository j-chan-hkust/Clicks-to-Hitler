# Hitler game solver
Returns the number of steps, and shortest path the wiki page: https://en.wikipedia.org/wiki/Adolf_Hitler

Just run it with the url as a input:

I've decided to abandon this one. Estimating around 50 unique links per page, even when we assume that average case is 3 layers deep, that's 125,000 nodes to explore, at 0.1s per node, is 3.5 hours of time, not to mention each layer means time taken gets a lot bigger.

Not feasible.
