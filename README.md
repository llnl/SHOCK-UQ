# Overview

This repository contains material for an uncertainty quantification (UQ) class on equation of state (EOS) that was presented at Science of Compression in Condensed Matter (SCCM) 2025. It includes a Python package called eosuq for analyzing linear shock compression data. The package performs Bayesian linear regression analytically and with Markov Chain Monte Carlo, and provides a bootstrap approach for comparison. The methods are demonstrated in a notebook on publicly available data contained in the notebooks directory. The dataset, from shock compression experiments on copper, is from pages 57-60 of Marsh, S. P. (1980), "LASL Shock Hugoniot Data".

## Published Work and Related Software

The analytical and bootstrap methods demonstrated in this repository were expanded into a published paper and a more comprehensive software package:

**Paper**: Bernstein, J., Myint, P. C., Lindquist, B. A., & Brown, J. L. (2026). A Tutorial on Bayesian analysis of linear shock compression data. *Journal of Applied Physics*, 140(3), 031101. https://doi.org/10.1063/5.0334353

**Software**: The repo is available at [BALSCD (Bayesian Analysis of Linear Shock Compression Data)](https://github.com/llnl/balscd).

If you use the code or methods from this repository in your research, please cite the paper:

```bibtex
@article{bernstein2026tutorial,
  title={A Tutorial on Bayesian analysis of linear shock compression data},
  author={Bernstein, Jason and Myint, Philip C. and Lindquist, Beth A. and Brown, Justin Lee},
  journal={Journal of Applied Physics},
  volume={140},
  number={3},
  pages={031101},
  year={2026},
  doi={10.1063/5.0334353}
}
```

## Getting Started

1. **Clone the repository**
```bash
    git clone https://github.com/LLNL/SHOCK-UQ.git
    cd SHOCK-UQ
```

2. **Create a virtual environment**
```bash
    python3 -m venv .venv
```

3. **Activate the virtual environment**
```bash
    source .venv/bin/activate
```

4. **Install the `eosuq` package with all dependencies**
```bash
    pip install -e .
```

5. **Launch Jupyter notebook** The notebook is located in the `notebooks` directory.

## Contributors

- Jason Bernstein (Lawrence Livermore National Laboratory)
- Justin Brown (Sandia National Laboratories)
- Beth Lindquist (Los Alamos National Laboratory)

## License

This software is distributed under the terms of the MIT license.  All new contributions must be made under the MIT license.

See [LICENSE](LICENSE) and [NOTICE](NOTICE) for details.

## Release

LLNL-CODE-2005336
