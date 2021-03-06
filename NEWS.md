# bayestestR 0.1.1

## Breaking changes

- `map_estimate()` now returns a single value instead of a dataframe and the `density` parameter has been removed. The MAP density value is now accessible via `attributes(map_output)$MAP_density`

## New functions / features

- Started adding plotting methods (currently in the [`see`](https://github.com/easystats/see) package) for `p_direction()` and `hdi()`

## Minor changes

- `p_direction`: improved printing
- Improved testing
- `rope()` for model-objects now returns the HDI values for all parameters as attribute in a consistent way

## Bug fixes

- `hdi()` returned multiple class attributes (#72)
- `plot.equivalence_test()` did not work properly for *brms*-models (#76).

# bayestestR 0.1.0

- CRAN initial publication and [0.1.0 release](https://github.com/easystats/bayestestR/releases/tag/v0.1.0)
- Added a `NEWS.md` file to track changes to the package
