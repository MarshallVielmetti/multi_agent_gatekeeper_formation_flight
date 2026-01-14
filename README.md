# Multi-Agent gatekeeper: Safe Flight Planning and Formation Control for Urban Air Mobility

## Quickstart

Clone this repo to a good location. 

Install the dependencies
```julia
] instantiate
] precompile
```

If you have any issues with `Dubins.jl`, 
```julia
] rm Dubins 
] add https://github.com/dev10110/Dubins.jl.git
```
Tested with `Dubins.jl v1.2.3` on Apr 7 2025.

Consider citing the underlying work:
```
@article{agrawal2024gatekeeper,
  title={gatekeeper: Online safety verification and control for nonlinear systems in dynamic environments},
  author={Agrawal, Devansh Ramgopal and Chen, Ruichang and Panagou, Dimitra},
  journal={IEEE Transactions on Robotics},
  year={2024},
  publisher={IEEE}
}

@article{agrawal2024gatekeeper,
  title={Multi-Agent gatekeeper: Safe Flight Planning and Formation Control for Urban Air Mobility},
  author={Vielmetti, Thomas Marshall, Agrawal, Devansh Ramgopal and Panagou, Dimitra},
  journal={AIAA SciTec},
  year={2026},
  publisher={AIAA}
}
```

## License

```
Copyright (c) 2025 Devansh R Agrawal. All Rights Reserved.
```
