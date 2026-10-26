# Truck–drone routing (TSP-D) in Bacău and Neamț counties — data

Data supporting the manuscript *mathematics-4685793* submitted to MDPI *Mathematics*.

## Contents

### `data/` — input data
| File | Description |
|---|---|
| `matrice_distante.xlsx` | Road distance matrix (m), 176 × 176 nodes (depot + 175 localities) |
| `Orase.xlsx` | Node ID, latitude, longitude, name |
| `orase_combinat_bacau_neamt.xlsx` | Source list of the localities |
| `ruta_optima_tsp.txt` | Optimal truck TSP tour, one arc per line: `i j cost_m` |
| `benchmark_DMN/` | Benchmark instances and published optimal solutions of Dell'Amico et al. (2021), used for validation |

### `results/` — results reported in the manuscript
| File | Description |
|---|---|
| `tabele_manuscris.xlsx` | Tables of the manuscript (experiments E1–E8) |
| `rezumat_rezultate.txt` | Summary of the results of experiments E1–E8 |

## Benchmark source

Dell'Amico, M., Montemanni, R., Novellani, S. (2021). Benchmark instances and optimal solutions for the
traveling salesman problem with drone. arXiv:2107.13275. These instances are redistributed here unchanged,
for convenience; please cite the original source.

## License

The data in this repository (except `data/benchmark_DMN/`, which belongs to its original authors) is
released under the Creative Commons Attribution 4.0 International License (CC BY 4.0).
