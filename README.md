# ChenRegistry

This is my personal Julia package registry.

# Usage

Following the [Pkg.jl documentation](https://pkgdocs.julialang.org/v1/registries/#Adding-registries), this registry can be added as follows,

```julia
pkg> registry add https://github.com/physcxia/ChenRegistry.git
```

or using the [API](https://pkgdocs.julialang.org/v1/api/#Registry-API-Reference),

```julia
julia> using Pkg
julia> Pkg.Registry.add(RegistrySpec(url = "https://github.com/physcxia/ChenRegistry.git"))
```
