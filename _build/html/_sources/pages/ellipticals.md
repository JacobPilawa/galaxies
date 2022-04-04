# Elliptical Galaxies

## Brightness Profiles

```{image} ../figures/72.png
:width: 600px
:align: center
```


* Sersic profiles are not always the best descriptions of elliptical galaxies – we have two families of ellipticals. 
    * Core 
        * Higher $n$, have "missing light" near the center. Maybe BBH scouring? Maybe dissipationaless (i.e., no gas) mergers
        * Core radii scale with black hole sphere of influence / black hole mass
        * Typically more luminous and more massive
    * Coreless
        * Do not have the missing light at small radii. Maybe from dissipational mergers?

### Comparing to S0/Spheroidal Galaxies


* Importantly, spheroidal and S0 galaxies have very properties than true ellipticals
    * Core ellipticals are much more massive and have higher Sersic $n$
    * S0 bulges are more comparable to coreless ellipticals and fall on the relations.
    * They are much fainter at the same radii, and have more structure in the surface brightness profiles.
    * They also follow totally different luminosity functions – **ellipticals are much brighter than spheroidal galaxies**.

```{image} ../figures/73.png
:width: 600px
:align: center
```

## The Fundamental Plane

### Faber-Jackson Relation

* One of the first empirical laws discovered about elliptical galaxies is the tight correlation between the Luminosity $L$ and the stellar velocity disperison $\sigma$: $L\propto \sigma^{\sim 4}$ 

```{image} ../figures/74.png
:width: 600px
:align: center
```


### The Kormendy Relation

* Another relation is the Kormendy relation – the average surface brightness correlates tightly with the half-light radius. 

```{image} ../figures/75.png
:width: 600px
:align: center
```


### The Fundamental Plane

* It turns out that we can combine the two above relations (which are just projections of a more fundamental thing called the **Fundamental Plane of Elliptical Galaxies**): a relationship between the surface brightness, velocity dispersion, and effective radius. 
* Here are some projections of the Fundamental Plane:


```{image} ../figures/76.png
:width: 600px
:align: center
```

```{image} ../figures/77.png
:width: 600px
:align: center
```

* Elliptical galaxies are a homogeneous population!
    * Dwarf spheroidals do not fall on these relations.
    * Globular clusters do not fall on these relations. 

```{image} ../figures/78.png
:width: 600px
:align: center
```


#### Derivation from the Virial Theorem

We have the Fundamental Plane as:

$$
L \propto \sigma^{2.65} r_e^{0.65}
$$

and 

$$
r_e \propto \sigma^{1.24} I_e^{-0.82}
$$

where $\mu = -2.5\log_{10}I_e$. We can get these relations close with the virial theorem.

$$
2\langle K\rangle=-\langle U\rangle
$$

We can re-write the kinetic energy as:

$$
2\langle K\rangle=\left\langle\Sigma_{i=0}^{N} m_{i} v_{i}^{2}\right\rangle
$$

The bulk rotation of the galaxy is slow, but velocity dispersions can be huge! Thus, the impoortant component is the random motion of stars themselves – the **velocity dispersion**.

$$
\sigma = \langle v^2 \rangle - \langle v \rangle ^2
$$
Thus:

$$
2\langle K\rangle=\left\langle\sum_{i=0}^{N} m_{i} v_{i}^{2}\right\rangle \approx M_{\star} \sigma_{v}^{2}
$$

What about the potential energy? We have:

$$
    U = - C G \frac{M M_\star}{r_e}
$$

Putting what we have together, we have:

$$
    M_\star \sigma_v^2 = - G \frac{M M_\star}{r_e} \rightarrow M = K r_e \sigma_v^2 \text{ where } K \equiv \text{ constants}
$$

Let's write the surface brightness:

$$
    I_e = \frac{F}{\Omega} = \frac{L}{4\pi d^2} \frac{1}{\frac{\pi r_e^2}{d^2}} \propto \frac{L}{r_e^2}
$$

This is effectively the average surface brightness within $r_e$. Continuing on, we have...

$$
    L \propto r_e^2 I_e \rightarrow L \left(\frac{M}{L}\right) \propto r_e \sigma_v^2 \rightarrow r_e^2 I_e \left(\frac{M}{L}\right) \propto r_e \sigma_v^2
$$

We take this last equation and solve for $r_e$:

$$
    r_e \propto \left(\frac{M}{L} \right)^{-1} \sigma_v^2 I_e^{-1}
$$

Assuming that the mass-to-light ratio is constant, we have:

$$
    r_e \propto \sigma_v^2 I_e^{-1}
$$

The real scaling relation is $r_e \propto \sigma^{1.24} I_e^{-0.82}$.

**The majority of the "tilt'' of the fundamental plane is due to a changing mass-to-light ratio, but we assumed that it was constant!** This is a good sign that elliptical galaxies are dispersion supported. 


## Stellar Populations in Ellipticals

* Massive core ellipticals both form their stars earlier and on shorter-time scales than moreless ellipticals!
* By the time the Type Ia SN are going off, the elliptical has already used up all its gas and thus cannot continue to Fe enrich the ISM and the stars. 
    * This is why we are alpha enhanced – the Type II all went off and formed stars quickly, without the Fe enriching the ISM. 

```{image} ../figures/79.png
:width: 600px
:align: center
```

```{image} ../figures/81.png
:width: 600px
:align: center
```


## Evolution over Cosmic Time

* The quiescent galaxy population grows over time, though in particular, the most massive galaxies were already formed/in place at earlier times. We can see this in the evolution of the galaxy mass function with redshift:



```{image} ../figures/80.png
:width: 600px
:align: center
```

* The much smaller quiescent galaxies "red nuggets" at high redshift are thought to be the cores of modern day ellipticals. Outskirts build up over time by minor mergers.
    * This is to say that Early Type galaxies were smaller at earlier times. These much smaller galaxies formed the cores of modern day ellipticals, and the outskirts are built up over cosmic time by accretion of smaller galaxies ("minor mergers").

## Summary of Elliptical Galaxies

* Elliptical galaxies can be well-described by Sersic profiles. 
* Elliptical galaxies form a well-defined fundamental plane: the relationship between the effective radius, average surface brightness, and central velocity dispersion.
* The fundamental plane is tilted compared to what you derive from the virial theorem. 
    * Primarily due to mass-to-light variations.
* The Kormendy and Faber-Jackson relations are projections of the fundamental plane.
* Dwarf spheroidal galaxies and globular clusters do not fall on the fundamental plane of elliptical galaxies. They are not a part of the population of early type galaxies. 






