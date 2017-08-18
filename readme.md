This is a small pytorch library that contains some continuous implementations of
reinforcement learning algorithms.

Soon to be implemented:

* PPO
* A3C
* Parallelism
* Beta distribution policy

Bells and whistles:
* GAE and TD(lambda) estimators
* Variable step size for VPG (aka poor man's natural gradient)
* Entropy based exploration bonus
* Observation and advantage centering
* Pytorch wrapper for OpenAI Gym environments

To be implemented long term:

* DDPG
* NAF
* SVG
* I2A
* PGPE?
* Noisy Nets for Exploration
* CUDA support (should be trivial but I don't have a GPU to test on currently)

Maybe implemented in future:

* TRPO
* DXNN
* ACER and other off-policy methods
* Model-based methods

In the pipeline:
* ~Visdom~ Bokeh for progress tracking
* Package everything

Implemented:
* VPG plus + baseline confirmed to be correct and fast.
* No baseline implementation to test against, but adaptive VPG appears correct.