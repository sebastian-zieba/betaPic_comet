# A transiting exocomet detected in broadband light by TESS in the β Pictoris system

## Contents

This repository containts various files, which were used for the paper Zieba et al. (2019).

This repository containts the following folders:


* [modelling](https://github.com/sebastian-zieba/betaPic_comet/tree/master/modelling)

Contains the Jupyter Notebook with was used for the MCMC routine.



* [mast_files](https://github.com/sebastian-zieba/betaPic_comet/tree/master/mast_files)

Contains the light curve and target pixel files of beta Pictoris for Sector 4 through 7 downloaded from the MAST archive. 


* [lightcurve](https://github.com/sebastian-zieba/betaPic_comet/tree/master/lightcurve)

Contains three plots which also can be found in the publication and two Jupyter Notebooks: 

`betaPic_lightkurve.ipynb` analyses beta Pictoris using the `lightkurve` package.

`construction_of_the_lightcurve.ipynb` uses the files in [mast_files](https://github.com/sebastian-zieba/betaPic_comet/tree/master/mast_files). We also take a look at the closest stars using the `lightkurve` package. 



* [frequency_analysis](https://github.com/sebastian-zieba/betaPic_comet/tree/master/frequency_analysis)

Contains a Jupyter Notebook which was used in order to create two plots visible in the publication.
For the frequency analysis we used the software package [Period04](https://www.univie.ac.at/tops/Period04/) and the python package [SMURFS](https://github.com/MarcoMuellner/SMURFS).


* [betaPic_movies](https://github.com/sebastian-zieba/betaPic_comet/tree/master/betaPic_movies)

Contains four short (each ~1min and ~10MB) movies of beta Pictoris created by cutting out a 60x60 pixel area around the star using a jupyter notebook (which also can be found there). The mid-exposure time is marked just above the animation in BTJD (BJD - 2457000). Every movie shows the observations of beta Pic for a specific sector. No background objects (asteroids, ...) are visible before, during or after the dimming events. 



## Dependencies

You will need the python packages `numpy`, `matplotlib`,  `astropy` `lightkurve`, `scipy`, `emcee` and `corner`


## Quick start

1. Clone this repository with:

```python 
git clone https://github.com/sebastian-zieba/betaPic_comet 
```

2. Then run a Jupyter Notebook with:

```python 
jupyter notebook <name of the notebook>.ipynb 
```


## License

The code is released under a MIT licence.


