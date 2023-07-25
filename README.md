
# Hi, I'm Rodolfo André Cardoso Neves (Dirack) 👋

> Brazilian, 31 years old. Developer and PhD student with an emphasis on modeling and inversion of geophysical data at
> the Federal University of Pará (UFPA) (2021). Master's degree in geophysics (UFPA) (2015-2017).
> Bachelor's degree in geophysics (UFPA) (2010-2015). Contributor of Madagascar, an open-source
> seismic processing package, member of the Madagascar development team. Background
> experience in front-end web development with NodeJS, ReactJS and TypeScript, Eclipse RCP plugins with Java, C
> and Python development skills. Programming teacher and YouTuber.

<img alt="Gravimetric survey" src="https://github.com/Dirack/dirack/blob/master/capa.jpg" height=400 width=700>

###### Image: Working as a Staff Geophysicist on a gravimetric survey of GPR Geophysics Ltda (2014).


## Professional experience:

- **Freelance Web developer and geophysicist. Since May of 2023:**
I am a software developer with experience in Java and Python for desktop applications, plugins development, and web development with JavaScript, HTML/CSS, NodeJS, Bootstrap and PHP. Currently, I'm working as a freelancer.

- **Developer and Geophysicist Junior at Invision Geophysics. From March of 2022 to May of 2023. Rio de janeiro, Brazil:**
As a developer at Invision Geophysics, I have participated in the development of the Microseismic
Monitoring System M2S. I was responsible for the development of a REST API, to simulate the receivers
and servers responses to a dashboard, which I also developed with the orientation of senior
programmers from the company team. I have used modern web development technologies, such as
NodeJS, TypeScript, HTML/CSS, JavaScript and Bootstrap 4. I have also participated in the development
of a plugin for Halliburton's application, Decision Space Geoscience (DSG). This plugin is an Eclipe RCP
plugin, implemented in Java. Its purpose is to export seismic horizons, geoshapes and sections using the
google Protobuf format for data serialization. By the end, I had also participated in the development of a
geopressure calculator for Petrobrás. It was built using the Python language, plugin architecture, and the
core of an open source project for well log visualization called Gripy.

- **Staff Geophysicist on a gravimetric survey of GPR Geophysics Ltda. From July to December of 2014. São Paulo, São Paulo, Brazil:** As GPR Geophysics employee, I've worked on Agência Nacional de Águas (ANA) gravimetric survey for aquifer prospecting on karst relief. I was responsible for gravimetric data acquisition, data correction, and Bouguer anomaly maps construction.

- **Internship - Gravimetric survey of UNIFAP/UFPA/CNPQ/ANP Research project. From November to December of 2013. Macapá, Amapá, Brazil:** As a member of the UNIFAP/UFPA/CNPQ/ANP research project for potential fields I've worked in gravimetric and magnetic data acquisition along Araguarí river, with the purpose of obtain the basement relief in that area.

## Youtuber - Programming teacher

I teach computer programming on my Youtube chanel, [Geofisicando](https://www.youtube.com/channel/UCi5XD5PCQtPrIRD0H_GJvag) (portuguese material). We teach
several programming languages, such as C, Fortran, Shell Script, Python and others. Please subscribe and share!

Some of our courses have digital certificate available on Workover Academy platform (our partner, with several online courses available for free). Please check it out on the following video: [Como conseguir o seu primeiro emprego como programador? A nova parceria do canal pode te ajudar!](https://www.youtube.com/watch?v=5neZRO3yvDI)

##  Member of the Madagascar Developers team since 20/08/2021
> Madagascar Developer: Madagascar is an Open-Source Software Package for Multidimensional Data Analysis and seismic processing

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

