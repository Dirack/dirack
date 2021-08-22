
# Hi, I'm Rodolfo André Cardoso Neves (Dirack) 👋
> Phd's Student with emphasis in Modelling and Inversion of Geophysical Data at Federal University of Pará (UFPA) (2017-2021).
> Master's degree, Geophysics (UFPA) (2015-2017). Bachelor's degree, Geophysics (UFPA) (2010-2015)

<img alt="Gravimetric survey" src="https://github.com/Dirack/dirack/blob/master/capa.jpg" height=400 width=700>

###### Image: Working as a Staff Geophysicist on a gravimetric survey of GPR Geophysics Ltda (2014).

###  Member of the Madagascar Developers team since 20/08/2021
> Developer of Madagascar: Open-Source Software Package for Multidimensional Data Analysis

#### ✨ My contributions:

  - [Programs to Madagascar open-source seismic processing package](https://github.com/ahay/src/tree/master/user/dirack):
    - **sfvfsacrsnh:** is a C programs adapted to the Madagascar package. The main objective of this program is to optimize the zero offset Common Reflection Surface (CRS) parameters (RN, RNIP, BETA) that best fits a Non-hyperbolic CRS approximation surface with a reflection traveltime surface extracted from a seismic data cube
(seismic data organized in CMP x Offset X Time coordinates). The parameters optmization is achieved using Very Fast Simulated Aneelling (VFSA) global optimization algorithm. The result of that parameters optmization is used in CRS stacking and NIP tomography.

    - **sfnhcrssurf:** is a C programs adapted to the Madagascar package. The main objective of this programs is to build the Non-hyperbolic CRS surface using zero-offset CRS parameters obtained with _sfvfsacrsnh_ program.
    
    - **sfcrestack:** Common Reflection Element (CRE) stacking.
    - **sfcretrajec:** Calculate CRE trajectory on CMP x Offset plane given zero-offset CRS parameters (RN, RNIP, BETA)
    - **sfgetcregather:** Build CRE gather given CMP X Offset CRE trajectory coordinates and interpolated data cube- 
    - **sfgetcretimecurve:** Calculate CRE traveltime curve t(m,h) given CRS zero-offset parameters (RN, RNIP, BETA)



- New Madagascar Computational Recipes:
    - [kimodel.py](https://github.com/ahay/src/blob/master/book/Recipes/kimodel.py), 
    to generate a multi-layer model and apply Kirchhoff-Newton modeling on it.
    - [velocityAnalysis.py](https://github.com/ahay/src/blob/master/book/Recipes/velocityAnalysis.py),
    to do velocity Analysis, automatic picking, NMO correction and stack.
    - [pefInterpolation.py](https://github.com/ahay/src/blob/master/book/Recipes/pefInterpolation.py),
    to increase CMP data sampling with Predictive Adaptative Error Filters (PEF) interpolation.
    - [creGatherStack.py](https://github.com/ahay/src/blob/master/book/Recipes/creGatherStack.py),
    to do CRE stacking.

###### A "computational recipe" is a python script that defines functions to facilitate seismic processing steps with Madagascar package.
 
#### 🔭 Projects I'm currently working on:

- [ProSU](https://github.com/gpgeof/proSU): A Shell Script interface to Seismic Unix (SU) package.
- [creGatherStack](https://github.com/Dirack/creGatherStack): Common Reflection Element (CRE) Gather stacking.
- [creVelocityInversion](https://github.com/Dirack/creVelocityInversion): Velocity inversion algorithm using Common Reflection Element (CRE) traveltime approximation.
- [diffractionSimulator](https://github.com/Dirack/diffractionSimulator): SConscripts to simulate diffraction hyperbolas in the stacked section.
- [shellUnity](https://github.com/Dirack/shellUnity): Unity test framework for Shell Script (Portuguese).

#### 😄 How to reach me:

- rodolfo_profissional@hotmail.com (email)
- [Personal website](https://dirack.github.io)
- [Lattes](http://lattes.cnpq.br/1612438665756011)
- [Linkedin](https://www.linkedin.com/in/rodolfodirack/)
- [Facebook](https://www.facebook.com/rodolfo.neves.925)
- [Geofisicando (Youtube channel)](https://www.youtube.com/channel/UCi5XD5PCQtPrIRD0H_GJvag)

