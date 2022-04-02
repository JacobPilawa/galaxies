# Statistical Properties of Galaxies

## Luminosity Functions

* For reasons we don't totally understand, the distribution of galaxies as a function of luminosity and mass can be modeled as a Schecter function:

$$
\Phi(L) \mathrm{d} L=\Phi_{*}\left(\frac{L}{L_{*}}\right)^{\alpha} e^{-L / L_{*}} \mathrm{~d}\left(\frac{L}{L_{*}}\right)
$$



```{image} ../figures/21.png
:width: 500px
:align: center
```



* $L_\star$ is the inflection point of the function
* $\alpha$ is the faint end slope
* $\Phi_*$ is a normalization with units of number per volume

* For faint galaxies, we have a power low behavior in $\alpha$
* For bright galaxies, we have an exponential decline in the number of galaxies

* In the local volume, the Milky Way is an $L_\star$ galaxy of roughly $10^{10} L_\odot$ 
* Note that **individual galaxy types do not necessarily obey Schecter functions, but the sum of galaxies do.**


```{image} ../figures/22.png
:width: 500px
:align: center
```


### Challenges of Observation

* You need distances – redshifts in particular for low $z$ galaxies do reflect both the distance the peculiar motion
* For the same luminosity and $z$, low-surface brightness galaxies are harder to detect
* **Malmquist bias:** brighter galaxies can be traced to larger distances than fainter galaxies. Solutions:
    * Only consider a range in luminosity and distance for which you are complete
    * Apply volume corrections for each observed luminosity

```{image} ../figures/23.png
:width: 500px
:align: center
```

```{image} ../figures/24.png
:width: 500px
:align: center
```


### Luminosity Functions vs. Color

* **Redder galaxies dominate the bright end of the luminosity function – they're the biggest and brightest. Blue galaixes dominate the faint end.**

```{image} ../figures/25.png
:width: 500px
:align: center
```

### Luminosity Functions vs. Environment

* **There are more galaxies in denser environments. Also, the faint end slope gets steeper in low density environments – that means there are more low mass galaxies in dense environments.**

```{image} ../figures/26.png
:width: 500px
:align: center
```

### Physical Origin of the Luminosity Function

```{image} ../figures/29.png
:width: 500px
:align: center
```


## Mass Functions

```{image} ../figures/27.png
:width: 500px
:align: center
```


* Remember that redder galaxies have larger mass-to-light ratios. Thus, **the red galaxy mass functions moves to the right compared to the blue function when moving from luminosity to mass space.**


### Evolution of the Mass Function

* The mass function normalization changes in time.
    * **We can use the mass function to trace the building of mass over cosmic history. Near $z$ of $2$  or so, the blue and red galaxy mass functions are nearly on top of each other, whereas they have bifurcated today.**

```{image} ../figures/28.png
:width: 500px
:align: center
```


## UV Luminosity Function

```{image} ../figures/30.png
:width: 500px
:align: center
```

* We can trace the SFR density over cosmic time by looking at the UV luminosity function. 
* At high redshift, we have a low number density of galaxies because galaxies have not formed yet! 


* Integrating the UV luminosity function, we can get the SFR density over cosmic time. 
    * **SFR peaks near $z\sim 2$ or $3$, and declines steeply at high redshift. The peak epoch was around 2 or 3 billion years after Big Bang.**
* To make these measurements, we fit Schecter functions to UV luminosity functions at each redshift bin. We integrate for the total UV luminosity at that time, and use a stellar population model to infer the # of stars, masses, and SFRs. 

```{image} ../figures/31.png
:width: 500px
:align: center
```

