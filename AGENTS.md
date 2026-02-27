# MoM_Visualizing.jl - Visualization Layer

2D/3D visualization based on Makie (CairoMakie/GLMakie).

## Source Tree

```
src/
├── MoM_Visualizing.jl      # Main module, defines themes
├── lines_plot.jl           # Line plot templates
├── polar_plot.jl           # Polar coordinate plots
├── Sources.jl              # Source visualization
├── far_field_viz.jl        # Far-field visualization
├── Solvers.jl              # Solver convergence curves
├── mesh_viz.jl             # Mesh visualization
├── array_viz.jl            # Antenna array visualization
└── lebedev_viz.jl          # Lebedev sphere quadrature points
```

## Capabilities

| File | Visualization |
|------|---------------|
| mesh_viz.jl | 3D mesh geometry |
| far_field_viz.jl | Radiation patterns |
| polar_plot.jl | RCS polar plots |
| array_viz.jl | Antenna array layout |
| Solvers.jl | Convergence history |
| lebedev_viz.jl | Quadrature point distribution |
