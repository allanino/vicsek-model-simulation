# Vicsek Model Simulation

This is a simulation of the [Vicsek Model](http://www.wikiwand.com/en/Vicsek_model)
for [self-propelled particles](http://www.wikiwand.com/en/Self-propelled_particles).

I came across this model in [this Nature article](http://www.nature.com/news/the-physics-of-life-1.19105),
describing some advances in the field of [active matter](https://www.wikiwand.com/en/Active_matter).

## Configuration

You can tweak the model configuration by passing arguments to the URL. The following
parameters are available:

- `N`: number of particles in the simulation
- `v`: velocity of particles in pixels per update
- `n`: noise amplitude in radians to be added to particles' velocity direction
- `r`: radius in pixels to look for neighboring particles in the average direction computation
- `fps`: frames per second to draw
- `blur`: motion blur to apply from 0.0 to 1.0
- `bs`: body size of particles in pixels
- `ts`: tail size of particles in pixels
- `tw`: tail width of particles in pixels

For instance, to create a simulation with 500 individuals, noise amplitude of 2
radians and velocity of 10 pixels you can access [http://allanino.me/vicsek-model-simulation/?N=500&n=2.0&v=10](http://allanino.me/vicsek-model-simulation/?N=500&n=2.0&v=10).
