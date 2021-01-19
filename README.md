# Parametric-Drug-Diffusion-Modelling

Code for [Ting Xu](https://xugroup.berkeley.edu) rotation at UC Berkeley
Used interpolation to model drug diffusion from many pieces of literature data.

Originally intended for project on [Estimating Tumor Vascular Permeability using a Diffusive Flux Model](https://doi.org/10.1021/acsbiomaterials.9b01590)

Code is able to produce plots like those seen below. A function will fit to the literature data based on the [Starling Equation](https://en.wikipedia.org/wiki/Starling_equation) of drug diffusion. 

![](Diffusive%20Flux%20Fitted%20Literature%20Data/Aggregate%20Model%20Fits/Chen%2C%20Zhang/doxorubicin%20(DOX)%20and%20paclitaxel.svg)


From there, we are able to separate the diffusive and convective portions of flow.

![](https://raw.githubusercontent.com/EmaadKhwaja/Parametric-Drug-Diffusion-Modelling/d7890297603b3d9f80a76eacd28026ed4fc19997/Diffusive%20Flux%20Fitted%20Literature%20Data/Model%20Component%20Fits/Cabral%2C%20Matsumoto/BxPC3%20pancreatic%20tumor%2050%20nm%20Components.svg)
