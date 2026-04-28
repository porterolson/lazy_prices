# Porter Olson Lazy Prices Repo
Lazy Prices Replication &amp; Extension Repo

`lazy_prices_fixing.ipynb` is my notebook for replicating _Lazy Prices_ using quintile sorts. 

`10k_get_alpha_no_lag_signal.ipynb` is my notebook for getting the MVE alpha and submitting a backtest for the signal (note I do not lag the signal because I use forward returns)

`forward-returns.ipynb` is my notebook for correctly calculating the returns of the backtested weights.

`testing_metrics` is a folder full of my jupyter notebooks for testing different similarity metrics (e.g. SBERT vectorization, TF-IDF, Distrubitonal Metrics, etc)

`Lazy_Prices_Research_Report.pdf` is my report highlighting all the research that I have done regarding this signal.

----


`10k_get_alpha.ipynb` is my file to generate the alpha for my MVE backtest, located in `old`.

`10k_get_alpha_kl.ipynb` is the file for the KL-Divergence version of it. These are both in the `old` directory which used incorrect backtesting return logic.

`gen_chart_table.ipynb` is my file to generate the tables and charts for my MVE backtest (also in `old`).

_Note I only have 10-K data whereas they have 10-K and 10-Q data._

Here is an interesting paper that talks about how Gen AI usage is going up finanical reporting. Perhaps there is some signal to be found here.
Paper: [https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4986017](url)
