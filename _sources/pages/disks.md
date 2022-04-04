# Disk Galaxies

## Disk Properties

* Often, the surface brightness profiles are not well fit by single componenets – there's typically a central bulge and an outer disk which need to be fit separately. 
* It's approximately exponential beyond the bulge, though. 

```{image} ../figures/82.png
:width: 600px
:align: center
```

* Random Facts:
    * There's a **mass-size relation** More massive disk galaxies are larger
    * Older disks are more massive and brighter
    * Older, more massive disks rotate faster $(\sim 150$ km/s)
    * Brighter, more massive galaxies are more metal rich (approximately solar)
    * More metal rich disks also rotate faster
    * **Color Gradients:**
        * Colors become bluer with increase radius/decreasing surface brightness
        * Later type galaxies are bluer overall


## Bulge Properties

* There are two types of bulges: classical and pseudo-bulges:
    * Classical bulges typically live in disk galaxies with smooth light distributions
        * They are somehwat similar to elliptical galaxies
        * Often do not rotate
    * Pseudo-bulges typically live in disk galaxies with spiral structure and nuclear star formation
        * Light is typically dominated by young stars

```{image} ../figures/83.png
:width: 600px
:align: center
```


* Pseudo-bulges
    * Typically have lower Sersic $n$ , magnitude, and surface brightness
    * Are rapidly rotating 
    * Have central star formation (see image below)

```{image} ../figures/84.png
:width: 600px
:align: center
```


## Extent of Stellar and Gas Disk, Rotation Curves 

* HI is optically thin (you can see all the mass) and is typically 2-3 times more extended than the disk itself
* This makes HI a great way to probe the dark matter halo, and allows us to measure rotating curves to very large radii

```{image} ../figures/85.png
:width: 600px
:align: center
```

```{image} ../figures/86.png
:width: 600px
:align: center
```

* And here are Rubin's rotation curves from H$\alpha$:

```{image} ../figures/87.png
:width: 600px
:align: center
```


## The Tully-Fisher Relation

* Measuring maximum rotational velocities (aka measuring the dark matter mass), corrected for inclination effects, gives a scaling relation between rotational velocity and luminosity: **The Tully Fisher Relation!**
* In practice, you typically measure the velocities from HI, get cepheids for distances.

$$
L \propto V_{max}^\alpha \text{ for } \alpha=3-4
$$

```{image} ../figures/88.png
:width: 600px
:align: center
```


* Another scaling relation was found between mass (instead of luminosity), and this is called the **Baryonic Tully-Fisher relation**.

```{image} ../figures/89.png
:width: 600px
:align: center
```

### Derivation

In much the same way we could get close to the Fundamnetal Plane from the virial theorem, we can get close to the Tully-Fisher relation.

The empirical version is $L \propto v_{max}^{3.4}$. Let's start with the virial theorem:

$$
    2 \langle K \rangle = - \langle U \rangle 
$$

Following last time:

$$
    \langle K \rangle = \frac12 M \langle v^2 \rangle \rightarrow \frac12 C_1 M \langle v_{max}^2 \rangle
$$

$$
    U = -C_2 \frac{G M^2}{r_e}
$$

We now have:

$$
    M C_1 v_{max}^2 = C_2 \frac{GM^2}{r_e} \rightarrow M = \frac{r_e v_{max}^2}{C_1 C_2 G}
$$

Do the same algebraic trick as last time, multiply by the mass-to-light ratio:

$$
    L = \left(\frac{M}{L}\right)^{-1} \frac{r_e v_{max}^2}{C_1 C_2 G}
$$

We now **assert a constant mass-to-light** ratio:

$$
    L \propto r_e v_{max}^2
$$

We make another assertion (though it's egregious). Let's say we have an exponential surface brightness profile:

$$
    I(r) = I_0 e^{\frac{-r}{r_0}}
$$

where $r_0 \propto r_e$. Taking this SBP, we find:

$$
    L_{tot} \propto 2\pi I_0 r_0^2
$$

It turns out there is a thing called **Freeman's Law**, which says there is an approximate constant surface brightness for disk galaxies. Using this as an assertion:

Thus,

$$
    L \propto r_0^2 \propto r_e^2 \rightarrow r_e \propto \sqrt{L}
$$

Returning to before:

$$
    L \propto \sqrt{L} V_{max}^2 \rightarrow \boxed{L \propto v_{max}^4}
$$

**The Tully-Fisher is powerful for the same reasons as the Fundametnal plane.**


## Spiral Structure

* Spiral arms are most prominent at wavelengths which probe recent star formation.

```{image} ../figures/90.png
:width: 600px
:align: center
```

* Distribution of material
    * Dust lanes, CO are typically found on the inner edge of spiral arms – the sights of ongoing star formation! Stars will be formed on the inner edge and then drift behind, making up the actual arms themselves

```{image} ../figures/91.png
:width: 600px
:align: center
```

    * HI traces the spirals themselves and are the reservoirs for future star formation

```{image} ../figures/92.png
:width: 600px
:align: center
```

### Types of Spirals

* Grand design with two strong spiral arms (20%) vs. multiple arm spirals vs. flocculent spirals (with lots of chaos, no clear spiral arms but spiral structure)
    * Flocculent arms/spirals are associated with ongoing star formation
* Depends on wavelength!

### Trailing and Leading Arms

* Projection effects make it hard to know the rotation direction – need to measure distance to front and back of spiral, or use dust obscuartion to infer the rotation direction and thus the leading or trailing arms


### Origin of Spiral Arms

* Flocculent structure could be the result of differential rotation, but stable spiral arms seen in grand design spirals cannot be due to differential rotation alone. The arms would fragment and dissolve much faster than we see.
* Instead, we think of spiral density waves just like in a traffic jam
    * Maybe these originate in asymmetries in the potential which has been seen in simulation 
    * Maybe it's induced in galaxy encounters


* Density Wave Theory
    * Stars form on inner arms (so more dust and molecular gas). While the new  stars travel through the arms, the molecular gas gets dissociated (into HI).  The most massive (OB) stars die out fast, before the stars move out of the  arms. Thus you see star formation primarily in the arms. 
    * The gas is more collisional than the stars, and thus the gas is swept up into regions more easily than stars. Stars form on inner arms (so more dust and molecular gas). While the new stars travel through the arms, the molecular gas gets dissociated (into HI). The most massive (OB) stars die out fast, before the stars move out of the arms. Thus you see star formation primarily in the arms.


## Barred Spirals

* General facts
    * Common in ⅓ to ⅔ of spirals
    * Isophotes not fit by ellipses, more retangular
    * Probably flat in the disk plane
    * Bars are straight and stars stay in the bar
    * Bars rotate along with the pattern speed
    * Bars are **not** density waves but density waves likely shaped orbits of the inner stars
    * Bars can help drive density waves in the disk and maintain spiral structure
    * Bars are long-lived, easy to form in simulations

```{image} ../figures/93.png
:width: 600px
:align: center
```

## Disks at High Redshift

* At higher $z$, star forming disks are much more irregular and clumpy
* Despite the optical morphology being lumpy, the actual underlying mass is quite smooth

```{image} ../figures/94.png
:width: 600px
:align: center
```

* **The Tully Fisher** relationship seems to hold at higher redshifts – the slope simply follows from dark matter halo properties.

```{image} ../figures/95.png
:width: 600px
:align: center
```


## Summary of Disk Galaxies

* The surface brightness profiles are approximately exponential
* More massive disks are on average more metal-rich, older, rotate faster, redder, and larger
* The outer parts of disks are generally bluer and of lower metallicity than the inner part
* Disk galaxies have flat rotation curves
* Disk galaxies fall on the Tully-Fisher relation, a tight correlation between luminosity/mass and rotational velocity. 














