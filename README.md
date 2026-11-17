### Quant research & machine learning on Apple Silicon

I build trading-research systems that are **honest about luck**: walk-forward testing, explicit costs,
stated biases, and a Deflated Sharpe on every result. The heavy compute runs overnight on Apple Silicon
(LightGBM on the CPU, MLX on the GPU), and the results land here every morning.

#### Projects (one repo each)

| repo | what | status |
|---|---|---|
| **[quant](https://github.com/vendraholdings/quant)** | ML stock ranking on the S&P 500: ~2,000 LightGBM + MLX models a night, walk-forward with a 40-day embargo. Best: **Sharpe 1.03 after costs, Deflated Sharpe probability 99.9%** | live, updated nightly |
| earnings-vol | earnings event study, post-earnings drift, realised vs implied earnings moves from my own daily option snapshots | building |
| mlx-finance | deep learning for markets in MLX, plus MLX vs PyTorch-MPS benchmarks | next |
| portfolio-risk | HRP / mean-variance / risk parity with costs, PCA factor risk model, VaR & ES backtests | next |

#### Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![MLX](https://img.shields.io/badge/MLX-000000?logo=apple&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B)
![polars](https://img.shields.io/badge/polars-CD792C?logo=polars&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?logo=duckdb&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?logo=react&logoColor=61DAFB)
