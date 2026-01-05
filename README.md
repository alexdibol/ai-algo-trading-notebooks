# AI & Algorithmic Trading — Official Resources

This collection represents the result of an unusually **complete, disciplined, and end-to-end effort** to document, explain, and implement modern algorithmic trading systems — from first principles to production-aware and governance-conscious architectures.

Across **three full PDF volumes**, a dedicated **user manual**, and **twenty-five tightly aligned Google Colab notebooks**, the project is designed as a **coherent learning and implementation path**, not as a loose anthology of topics or disconnected examples.

The objective of the collection is explicit:

- to treat **algorithmic trading as a system**, not as a bag of tricks,
- to close the persistent gap between **theory, code, and real-world constraints**,
- to provide artifacts that are **reproducible, auditable, and extensible**,
- and to model what disciplined research-to-production thinking looks like in practice.

This is not a promise of easy alpha.  
It is an invitation to think clearly about markets, data, decisions, and risk — and then to implement those ideas with rigor.

The materials below constitute the **complete and authoritative entry point** to the collection.

---

## 📘 Book Volumes and User Manual (PDF)

All PDFs are hosted as **GitHub Release assets** to ensure stable, citable links.

- **Volume I — Foundations of Algorithmic Trading**  
  https://github.com/alexdibol/ai-algo-trading-notebooks/releases/download/algo_trading-volumes-v01/VOLUME.1.FOUNDATIONS.OF.ALGORITHMIC.TRADING.pdf

- **Volume II — Backtesting & Strategy Families**  
  https://github.com/alexdibol/ai-algo-trading-notebooks/releases/download/algo_trading-volumes-v01/VOLUME.2.FOUNDATIONS.OF.ALGORITHMIC.TRADING.pdf

- **Volume III — Machine Learning, Portfolio Construction, Execution & Deployment**  
  https://github.com/alexdibol/ai-algo-trading-notebooks/releases/download/algo_trading-volumes-v01/VOLUME.3.FOUNDATIONS.OF.ALGORITHMIC.TRADING.pdf

- **User Manual — How to Navigate the Collection**  
  https://github.com/alexdibol/ai-algo-trading-notebooks/releases/download/algo_trading-volumes-v01/USERS.MANUAL.FOUNDATIONS.OF.ALGORITHMIC.TRADING.pdf

---

## 📓 Companion Colab Notebooks (Chapters 1–25)

Each chapter in the book is paired with **exactly one executable Google Colab notebook**.

These notebooks are not illustrative demos; they are **reference implementations** designed with the same constraints discussed in the text.

Core design principles:

- one chapter, one notebook,
- explicit time awareness and causality,
- synthetic-first demonstrations by default,
- transparent implementations over black-box abstractions,
- governance-native structure (seeds, parameters, manifests, artifacts).

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

## ⚖️ License

This project is released under the **MIT License**.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

## ⚠️ Disclaimer and Use of AI Tools

This collection is provided for **educational and research purposes only**. It does not constitute investment advice, trading advice, or a recommendation to engage in any particular trading strategy or financial activity.

Market behavior is uncertain, and any application of the ideas, code, or methodologies presented here is undertaken **entirely at the reader’s own risk**.

Artificial intelligence tools may have been used to **assist** in aspects of editing, code generation, formatting, or drafting during the development of this collection.  
However, **conceptual design, methodological choices, system architecture, editorial judgment, integration, and final responsibility** for the content, structure, and conclusions of the work remained **under direct human control** throughout.

The author assumes full responsibility for the coordination, design, and construction of the collection as a whole.
