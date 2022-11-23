# Cosmic Chronometer, data and systematic effects

## Here, we provide a simple notebook to generate the CC data with and without systematic effects

### The code mainly base on the work of <a href="https://ui.adsabs.harvard.edu/abs/2020ApJ...898...82M/abstract">Moresco et al. (2020)</a>
#### cosmic chronometers (CC) covariance is defined as the combination of a statistical and systematic part:

```math
{\rm Cov}_{ij}= {\rm Cov}_{ij}^{\rm stat}+ {\rm Cov}_{ij}^{\rm syst}
```
where the systematic part is decomposed in several contributions:

```math
{\rm Cov}_{ij}^{\rm syst}= {\rm Cov}_{ij}^{\rm met}+ {\rm Cov}_{ij}^{\rm young}+ {\rm Cov}_{ij}^{\rm model}
```

where the model term is also decomposed in the following terms

```math
{\rm Cov}_{ij}^{\rm model}={\rm Cov}_{ij}^{\rm SFH}+{\rm Cov}_{ij}^{\rm IMF}+{\rm Cov}_{ij}^{\rm st. lib.}+{\rm Cov}_{ij}^{\rm SPS}
```

### for detials of each term see <a href="https://ui.adsabs.harvard.edu/abs/2020ApJ...898...82M/abstract">Moresco et al. (2020)</a>
