# ParameterDistributions

```@meta
CurrentModule = EnsembleKalmanProcesses.ParameterDistributions
```

```@docs
Parameterized
Samples
Constraint
ParameterDistribution
no_constraint
bounded_below
bounded_above
bounded
length(c::CType) where {CType <: ConstraintType}
size(c::CType) where {CType <: ConstraintType}
n_samples
get_name
get_dimensions
get_n_samples
get_all_constraints
batch
get_distribution
sample
get_logpdf
mean
var
cov
transform_constrained_to_unconstrained
transform_unconstrained_to_constrained
```
