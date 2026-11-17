### Quant research & machine learning on Apple Silicon

I build trading-research systems that are **honest about luck**: walk-forward testing, explicit costs,
stated biases, and a Deflated Sharpe on every result. Heavy compute runs on Apple Silicon:
LightGBM on the CPU, MLX on the GPU.

#### Projects (one repo each)

| repo | what | status |
|---|---|---|
| **[quant](https://github.com/vendraholdings/quant)** | ML stock ranking on the S&P 500: ~2,000 LightGBM + MLX models a night, walk-forward with a 40-day embargo. Best: **Sharpe 1.03 after costs, Deflated Sharpe probability 99.9%** | live |
| earnings-vol | earnings event study, post-earnings drift, realised vs implied earnings moves from my own daily option snapshots | building |
| mlx-finance | deep learning for markets in MLX, plus MLX vs PyTorch-MPS benchmarks | next |
| portfolio-risk | HRP / mean-variance / risk parity with costs, PCA factor risk model, VaR & ES backtests | next |

#### Stack

**AI / machine learning**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![MLX](https://img.shields.io/badge/MLX-000000?logo=apple&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?logo=huggingface&logoColor=black)
![LLM agents](https://img.shields.io/badge/LLM_agents-412991)
![Transformers](https://img.shields.io/badge/Transformers-6E40C9)
![NLP](https://img.shields.io/badge/NLP-0E7C86)

**Quant & data**  
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![polars](https://img.shields.io/badge/polars-CD792C?logo=polars&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?logo=scipy&logoColor=white)
![cvxpy](https://img.shields.io/badge/cvxpy-4B8BBE)
![statsmodels](https://img.shields.io/badge/statsmodels-3F4F75)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?logo=duckdb&logoColor=black)
![Apache Parquet](https://img.shields.io/badge/Apache_Parquet-50ABF1?logo=apacheparquet&logoColor=white)

**Visualisation & research**  
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?logo=plotly&logoColor=white)
![three.js](https://img.shields.io/badge/three.js-000000?logo=threedotjs&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C)
![Typst](https://img.shields.io/badge/Typst-239DAD?logo=typst&logoColor=white)

**Software engineering**  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?logo=expo&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![uv](https://img.shields.io/badge/uv-DE5FE9?logo=uv&logoColor=white)
