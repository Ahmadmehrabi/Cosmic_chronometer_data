# Cosmic Chronometer, data and systematic effects

## Here, we provide a simple notebook to generate the CC data with and without systematic effects

### The code mainly base on the work of <a href="https://ui.adsabs.harvard.edu/abs/2020ApJ...898...82M/abstract">Moresco et al. (2020)</a>
#### cosmic chronometers (CC) covariance is defined as the combination of a statistical and systematic part:

```math
{\rm Cov}_{ij}= {\rm Cov}_{ij}^{\rm stat}+ {\rm Cov}_{ij}^{\rm syst}
```
where $`{\rm Cov}_{ij}^{\rm syst}`$, for simplicity and transparency, is decomposed in several contributions:

```math
{\rm Cov}_{ij}^{\rm syst}= {\rm Cov}_{ij}^{\rm met}+ {\rm Cov}_{ij}^{\rm young}+ {\rm Cov}_{ij}^{\rm model}
```

where:
- $`{\rm Cov}_{ij}^{\rm met}`$ is the contribution to the covariance matrix due to uncertainty in the estimate fo the stellar metallicity;
- $`{\rm Cov}_{ij}^{\rm young}`$ is the part of the covariance matrix affected by an eventual residual young component in galaxy spectra (see <a href="https://ui.adsabs.harvard.edu/abs/2018ApJ...868...84M/abstract">Moresco et al. (2018)</a>);
- $`{\rm Cov}_{ij}^{\rm model}`$ is the contribution to the covariance matrix arising from modelling, that, in turn, can be decomposed in:
```math
{\rm Cov}_{ij}^{\rm model}={\rm Cov}_{ij}^{\rm SFH}+{\rm Cov}_{ij}^{\rm IMF}+{\rm Cov}_{ij}^{\rm st. lib.}+{\rm Cov}_{ij}^{\rm SPS}
```
where:
- $`{\rm Cov}_{ij}^{\rm SFH}`$ is the contribution to the model covariance matrix due to uncertainty in star formation history;
- $`{\rm Cov}_{ij}^{\rm IMF}`$ is the contribution to the model covariance matrix due to uncertainty in the IMF adopted;
- $`{\rm Cov}_{ij}^{\rm st. lib.}`$ is the contribution to the model covariance matrix due to uncertainty in the stellar library adopted;
- $`{\rm Cov}_{ij}^{\rm SPS}`$ is the contribution to the model covariance matrix due to uncertainty in the stellar population synthesis model adopted.
