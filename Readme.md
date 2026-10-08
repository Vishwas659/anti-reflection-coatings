# Anti-reflection coatings for silicon solar cells

Optimization of single- and double-layer anti-reflection coatings on silicon
using the transfer-matrix method and measured optical constants.

## Key results
- Single Si3N4 layer: average reflectance 35% → 8%
- SiO2/TiO2 double layer: 2.1% (solar-weighted loss 2.0%), matching the
  thin-film index-matching prediction
- Own transfer-matrix implementation, validated against `tmm` to ~1e-15, ~2.8× faster
- Solar-spectrum (AM1.5G) weighting changes the optimal SiO2/Si3N4 design
- Performance stays stable up to ~50° angle of incidence

## Data sources
Optical constants from refractiveindex.info: Si (Green 2008), Si3N4 (Luke et al. 2015),
SiO2 (Malitson 1965), TiO2 (Zhukovsky et al. 2015). Solar spectrum: ASTM G173 via pvlib.

## Run it
pip install -r requirements.txt, then open the notebook.