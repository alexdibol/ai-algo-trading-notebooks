# AI & Algorithmic Trading — Official Resources

This repository accompanies a **substantial, end-to-end body of work** on algorithmic and AI-driven trading systems.

Across **three full PDF volumes**, a dedicated **user manual**, and **twenty-five executable Google Colab notebooks**, this project takes the reader from first principles to fully governed, production-aware trading architectures.

This is not a collection of disconnected notes or examples.  
It is a **coherent system**, built with discipline around causality, time-awareness, reproducibility, and implementation fidelity.

The materials below represent the **complete and authoritative access point** to that work.

---

## 📘 Book Volumes (PDF)

All PDFs are hosted as **GitHub Release assets** to ensure stable, citable links.

- **Volume I — Foundations of Algorithmic Trading**  
  https://github.com/alexdibol/ai-algo-trading-notebooks/releases/download/algo_trading-volumes-v01/VOLUME.1.FOUNDATIONS.OF.ALGORITHMIC.TRADING.pdf

- **Volume II — Backtesting & Strategy Families**  
  https://github.com/alexdibol/ai-algo-trading-notebooks/releases/download/algo_trading-volumes-v01/VOLUME.2.FOUNDATIONS.OF.ALGORITHMIC.TRADING.pdf

- **Volume III — Machine Learning, Portfolio Construction, Execution & Deployment**  
  https://github.com/alexdibol/ai-algo-trading-notebooks/releases/download/algo_trading-volumes-v01/VOLUME.3.FOUNDATIONS.OF.ALGORITHMIC.TRADING.pdf

- **User Manual — How to Navigate the Collection**  
  (PDF release asset — to be added here once uploaded)

---

## 📓 Companion Colab Notebooks (Chapters 1–25)

Each chapter in the book is paired with a **one-to-one, executable Google Colab notebook**.

The notebooks are:
- deterministic (explicit seeds),
- time-aware (no leakage),
- synthetic-first by default,
- governance-native by construction.

**Notebooks repository**  
https://github.com/alexdibol/ai-algo-trading-notebooks

**Colab link format**  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/<FILE>.ipynb

---

## Part I — Foundations

Chapter 1 — Markets, Data, Logic of Algo Trading  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_1.ipynb

Chapter 2 — Python Quant Toolbox (NO pandas)  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_2.ipynb

Chapter 3 — Returns, Risk, Portfolio Math  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_3.ipynb

Chapter 4 — Time Series Anatomy for Trading  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_4.ipynb

Chapter 5 — Data Pipelines & Feature Engineering  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_5.ipynb

---

## Part II — Backtesting & Simple Strategies

Chapter 6 — Backtesting & Simulation  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_6.ipynb

Chapter 7 — Trend Following  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_7.ipynb

Chapter 8 — Mean Reversion & Pairs  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_8.ipynb

Chapter 9 — Factor Models & Cross-Sectional Strategies  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_9.ipynb

Chapter 10 — Volatility Modeling & Risk Targeting  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_10.ipynb

---

## Part III — Machine Learning

Chapter 11 — Supervised Learning for Forecasting Returns  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_11.ipynb

Chapter 12 — Regularization, Hyperparameters, Model Selection  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_12.ipynb

Chapter 13 — Neural Networks & Deep Learning in Trading  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_13.ipynb

Chapter 14 — Regime Detection & Hidden Markov Models  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_14.ipynb

Chapter 15 — Event-Driven Trading & News/Sentiment  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_15.ipynb

---

## Part IV — Portfolio, Execution, Reinforcement Learning

Chapter 16 — Portfolio Construction & Optimization  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_16.ipynb

Chapter 17 — Position Sizing, Leverage & Risk Management  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_17.ipynb

Chapter 18 — Transaction Costs, Slippage & Market Microstructure  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_18.ipynb

Chapter 19 — Reinforcement Learning for Trading Decisions  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_19.ipynb

Chapter 20 — Multi-Strategy & Multi-Horizon Systems  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_20.ipynb

---

## Part V — AI, Governance & Deployment

Chapter 21 — Model Risk, Explainability & Robustness  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_21.ipynb

Chapter 22 — Data Governance & Regulatory Context  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_22.ipynb

Chapter 23 — Infrastructure & Implementation Pathways  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_23.ipynb

Chapter 24 — AI-Native Trading Assistants & Agentic Architectures  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_24.ipynb

Chapter 25 — Capstone: A Full AI Trading System  
https://colab.research.google.com/github/alexdibol/ai-algo-trading-notebooks/blob/main/notebooks/chapter_25.ipynb

---

## 📌 Notes for Readers

- Notebooks are designed to be executed **top-to-bottom**.
- Random seeds, parameters, and assumptions are explicitly logged.
- Synthetic data is used by default; real-data adapters are isolated and optional.
- Chapters are intended to be followed **in order**, without conceptual fast-forwarding.
