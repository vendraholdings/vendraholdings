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
![SHAP](https://img.shields.io/badge/SHAP-FF0D57)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?logo=huggingface&logoColor=black)
![Transformers](https://img.shields.io/badge/Transformers-6E40C9)
![LLM agents](https://img.shields.io/badge/LLM_agents-412991)
![NLP](https://img.shields.io/badge/NLP-0E7C86)

**Quant & data**  
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![polars](https://img.shields.io/badge/polars-CD792C?logo=polars&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?logo=scipy&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-3F4F75)
![cvxpy](https://img.shields.io/badge/cvxpy-4B8BBE)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?logo=duckdb&logoColor=black)
![Apache Parquet](https://img.shields.io/badge/Apache_Parquet-50ABF1?logo=apacheparquet&logoColor=white)

**Visualisation & research**  
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?logo=plotly&logoColor=white)
![three.js](https://img.shields.io/badge/three.js-000000?logo=threedotjs&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C)
![Typst](https://img.shields.io/badge/Typst-239DAD?logo=typst&logoColor=white)

**Frontend**  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?logo=expo&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![Radix UI](https://img.shields.io/badge/Radix_UI-161618?logo=radixui&logoColor=white)

**Backend & databases**  
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?logo=pydantic&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?logo=sqlalchemy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)
![Drizzle ORM](https://img.shields.io/badge/Drizzle_ORM-C5F74F?logo=drizzle&logoColor=black)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?logo=twilio&logoColor=white)

**Cloud & DevOps**  
![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?logo=microsoftazure&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?logo=render&logoColor=black)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?logo=caddy&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![uv](https://img.shields.io/badge/uv-DE5FE9?logo=uv&logoColor=white)

**Systems & security**  
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![VPS administration](https://img.shields.io/badge/VPS_administration-555555)
![Server hardening](https://img.shields.io/badge/Server_hardening-2E3440)
![Penetration testing](https://img.shields.io/badge/Penetration_testing-B71C1C)
![Vulnerability assessment](https://img.shields.io/badge/Vulnerability_assessment-6A1B9A)
