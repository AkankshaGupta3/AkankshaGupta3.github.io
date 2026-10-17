---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research spans two connected themes: the fundamental fluid mechanics of how
ocean waves move water and the material it carries, and the applied problem of
forecasting coastal water quality for public health.

## Coastal water quality and pathogen forecasting
### Scripps Institution of Oceanography, with Prof. Falk Feddersen and Prof. Sarah N. Giddings

Beaches across the San Diego/Tijuana border region close regularly because of
elevated fecal indicator bacteria and viruses entering coastal waters through
river discharge and untreated wastewater. Predicting where and when
concentrations will be high requires understanding both the biological sources
and the physical transport &mdash; wave mixing, currents, freshwater discharge,
and dilution.

I work on the [**Pathogen Forecast Model (PFM)**](https://pfmweb.ucsd.edu/), a process-based five-day beach
advisory system for the region. The model tracks a passive dye tracer
representing wastewater; my analysis compares those dye predictions against
enterococcus concentrations measured by digital droplet PCR (ddPCR) at shoreline
monitoring stations, alongside ADCP currents, wave records, river flow gauge
data, and meteorological observations.

Alongside the model analysis, I built and operate the automated daily pipeline
behind the project's public diagnostics site. Each morning it ingests updated
forecast output and new observations, quality-controls continuous records from
the South Bay and Point Loma Ocean Outfall moorings, the Imperial Beach
mini-mooring, the Del Mar moorings, San Diego Bay tide gauges, and flow gauges
on the Tijuana River and at Punta Bandera, and publishes verification plots and
an interactive skill dashboard. I also process raw Nortek ADCP records from
three moorings into analysis-ready MATLAB and netCDF files, and compare HF radar
surface current fields against model output and in-situ currents.

**Key finding:** Tijuana River Estuary discharge dominates the enterococcus
signal at all Imperial Beach shoreline stations, with near-zero contribution
from sources further south. This directly constrains how the forecast model
should be structured and which inputs matter most for accurate advisories.

Related publications: Feddersen et al. (2026, *ES&T*); Gupta et al.
(*Ocean Modelling*, under review).

## Wave dynamics and Lagrangian transport
### Scripps Institution of Oceanography, with Prof. Xuanting Hao and Prof. William R. Young

Surface gravity waves do more than travel &mdash; they drive a net drift of water
particles known as Stokes drift, which transports pollutants, microplastics,
sediment, and biological material through the upper ocean.

I study how this drift is modified when surface waves interact with **internal
solitary waves**: large-amplitude waves that propagate beneath the surface along
density interfaces in the stratified deep ocean, often tens of metres tall while
nearly invisible from above. Using coupled theory validated against numerical
simulation, I showed that the internal wave substantially modulates surface
Stokes drift &mdash; enhancing it, reducing it, or reversing its direction
depending on the wave parameters.

Related publication: Gupta, Young & Hao (*Journal of Physical Oceanography*,
accepted).

## Wave&ndash;current&ndash;bathymetry interactions
### Ph.D. research, IIT Kanpur, with Dr. Anirban Guha

Two distinct mechanisms emerged from this work, both with implications for
coastal transport of pollutants and sediment.

**Current&ndash;bathymetry drift.** An alongshore current flowing over a
corrugated seabed generates a steady cross-shelf Lagrangian drift &mdash; even
with no surface waves present. This was a previously unrecognized transport
pathway across the continental shelf.
(*Journal of Fluid Mechanics*, 2022)

**Bragg-resonant modification of Stokes drift.** When a surface wave field
resonates with seabed corrugations at specific wavelength ratios, the resulting
wave triad substantially alters both the magnitude and direction of Stokes drift.
(*Physical Review Fluids*, 2021)

## Particle transport in upper-ocean turbulence
### Collaboration with the University of British Columbia, with Dr. Mona Rahmani

Microplastics and biogenic particles do not distribute uniformly in the ocean.
Using turbulence theory and large-scale simulation, this work identified the
preferential concentration mechanisms that cause particles of differing size and
density to cluster in specific regions of a turbulent flow &mdash; relevant to
marine pollution monitoring and ecosystem assessment.

Related publication: Rahmani, Gupta & Jofre (*International Journal of
Multiphase Flow*, 2022)

## Field work
### TFO Seamounts 2024 NESMA research cruise, R/V Roger Revelle, North Atlantic

One month at sea collecting and analyzing shipboard meteorological data to
quantify air&ndash;sea fluxes near the New England seamounts. Applied the COARE
algorithm and the Gibbs-SeaWater toolbox to compute turbulent heat and momentum
fluxes and mixed-layer depth, and compared flux estimates against epsilometer
measurements.
