# Stellar-MADE project

Antoine Lacquement

<img src="https://nicolascuello.github.io/Stellar-MADE/images/picture-AL.jpg" alt="AL picture" width="300"/>

### Summary of my career

I am a postdoctoral researcher at IPAG (Université Grenoble Alpes), where I have just joined the Stellar-MADE team, within the Odyssey group. My research focuses on the dynamics of young planetary and stellar systems, and on how circumstellar disks can be used to reveal their orbital architecture.

I studied at Université Grenoble Alpes, where I obtained a Bachelor's degree in Physics (2021), then a Master's degree in Astrophysics together with the Magistère program (2023). My Master's internship at IPAG, supervised by Hervé Beust, explored the possibility of an additional planet in the β Pictoris system, and became the starting point of my PhD.

I then did my PhD in the Exoplanets team at IPAG, under the supervision of Hervé Beust and Gaspard Duchêne, and defended it in October 2026. My thesis, entitled *"From observational constraints to dynamics: reconstructing the orbital architecture of young planetary systems"*, tackles a simple question: how can we recover the full architecture of a system when some bodies remain unseen and the others are only observed along short orbital arcs? Circumstellar disks keep the imprint of the gravitational perturbations they undergo, so their shape can be used as an indirect constraint. My approach combines Keplerian orbital fitting, to explore every solution compatible with the observations, with N-body simulations in which the disk is modeled as a set of particles, to rule out configurations that are unstable or that do not reproduce the observed disk. I applied it to [β Pictoris](https://doi.org/10.1051/0004-6361/202452632) and [TWA 7](https://doi.org/10.1051/0004-6361/202659112), whose disk morphologies both call for an additional planet, and started applying it to the young hierarchical triple [GG Tau A](https://doi.org/10.1051/0004-6361/202662146).

Along the way, I built two toolboxes that make our existing codes easier to use, each with a graphical interface to set up simulations and analyze their results: [Oracle](https://github.com/lacquema/Oracle), around an MCMC orbital-fitting code for high-contrast imaging and radial-velocity data, and [Astroide](https://github.com/lacquema/Astroide), around two N-body codes that model debris disks as test particles: RMVS3, which uses heliocentric coordinates and is suited to planetary systems, and HJS, which relies on hierarchical Jacobi coordinates and is suited to multiple stellar systems. Both are open source, operational, and still evolving.

During my PhD, I also took part in the 4th edition of the [GAES](https://static.hexagonarts.eu/hsn-2025-2026/le-gaes/index.html) (Groupe Artistique d'Exploration Scientifique), an art–science program bringing together artists, researchers, and PhD students for two sessions of a few days of talks and exchanges around the theme *"Savoir des limites et limites aux savoirs"* (the knowledge of limits and the limits of knowledge).

### Ongoing research

My postdoc carries on this work on GG Tau A, a young triple system made of a close pair of stars (Ab1–Ab2) and a third star (Aa), surrounded by a massive circumtriple disk whose large inner cavity, around 200 au, is still hard to explain. The first step is done: in a [first paper](https://doi.org/10.1051/0004-6361/202662146), I performed a joint orbital fit of the inner and outer orbits of the triple, which also constrains the individual stellar masses. I have also started the dynamical study with N-body simulations using HJS, partly through the work of an intern I supervised, and I will complete them to identify the configurations that carve this cavity. But unlike the debris disks of β Pictoris and TWA 7, the disk of GG Tau A is a protoplanetary disk, still rich in gas. The main goal of my postdoc is therefore to go beyond the N-body approach and test these solutions with hydrodynamical simulations using [Phantom](https://phantomsph.github.io/), to see how the gas changes the picture.

More broadly, I will study young hierarchical triples like GG Tau A and how they shape their disks, a topic that will gain momentum with Gaia DR4, which is expected to reveal many new triple systems. Gaia will also provide absolute astrometry, which I plan to integrate into Oracle alongside imaging and radial-velocity data to better constrain the orbits of these systems.

<img src="https://nicolascuello.github.io/Stellar-MADE/images/AL-ggtau-simulation.png" alt="N-body simulation of the GG Tau A disk" width="400"/>

*N-body simulation of the disk around GG Tau A after 4 Myr, for one of the orbital solutions found with Oracle. The gap carved near 200 au is driven by a secular resonance between the inner triple and the disk particles, and could contribute to shaping the observed cavity.*

### Recent highlight

An additional planet beyond β Pic b had already been suggested to explain the inner edge of the β Pictoris debris disk at about 50 au. In my [2025 paper](https://doi.org/10.1051/0004-6361/202452632), I confirmed with N-body simulations that the two known planets cannot carve this edge, and constrained the mass, semi-major axis, and eccentricity of such an additional planet. In June 2026, two independent teams announced the discovery of β Pictoris d, a third giant planet beyond β Pic b, with JWST and the VLT ([Gibbs et al.](https://arxiv.org/abs/2606.23789), [Sutlieff et al.](https://arxiv.org/abs/2606.23801)). Both discovery papers point to β Pic d as the planet carving the inner edge of the disk. Its semi-major axis (about 26 au) and mass (about 2.4 Jupiter masses) are also consistent with the mass–semi-major axis relation derived from my simulations, once extrapolated beyond the 1 Jupiter mass I had explored. This is an encouraging confirmation of the method developed in my thesis, which I am now pushing further with GG Tau A.

<img src="https://nicolascuello.github.io/Stellar-MADE/images/AL-betapic-d-prediction.png" alt="Predicted mass and semi-major axis of beta Pic d" width="450"/>

*Mass and semi-major axis of an additional planet (eccentricity 0.1) able to carve the inner edge of the β Pictoris disk at 50 au (green: my N-body simulations; blue band: fitted relation, extrapolated above 1 Jupiter mass), compared with the newly discovered β Pic d (red).*

[Back to home page](https://nicolascuello.github.io/Stellar-MADE/)
