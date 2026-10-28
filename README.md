# Financial Time-Series Forecasting

Exploratory and comparative neural-network experiments for financial-market time-series prediction, including GRU, LSTM, Bi-LSTM and other architectures.

## Project overview
The provided paper compares Apple (AAPL) and Bitcoin (BTC). A separate experimental notebook also explores Bitcoin, Ethereum and S&P 500. The paper reports GRU RMSE of 0.0152; **this figure is paper-reported, not reproduced here**. Review data leakage and scaling practices before treating the experiments as reliable benchmarks.

## Repository contents
- `notebooks/`: Original experimental notebooks where supplied.
- `docs/`: Original project paper or report where supplied.
- `data/`: Small supporting sample datasets where included.

## Getting started
1. Create a Python or R environment appropriate for the source notebooks/script.
2. Review notebook dependencies and local file paths before executing.
3. Obtain any missing datasets from their original providers and follow their licenses.
4. Execute the analysis or training steps and evaluate results before reusing reported metrics.

## Reproducibility status
This is an **archival portfolio import of the original academic work**, not a newly tested production pipeline. Notebook execution and reported scores have **not** been independently reproduced. Some notebooks rely on Google Colab/Kaggle paths and may require adaptation.

## Next improvements
- Document exact environments and dataset versions.
- Eliminate hard-coded data paths and add clear run commands.
- Validate train/test splits and leakage prevention.
- Add automated tests and concise, independently reproduced metrics.

## Author
Tousif Anam — [GitHub](https://github.com/Tousif-Anam)
