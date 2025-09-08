# Water-Level Time-Series (Difficult Run, VA)

Clean, reproducible time-series analysis of river discharge & gage height.  
Includes an interactive HTML report, a tiny sample dataset, and key plots for fast skim.

**What’s inside**
- `docs/index.html` – full report (enable GitHub Pages → main /docs to view online)
- `data/sample/difficult_run_10yr_data.csv` – 5-day slice for demos
- `results/figures/` – showcase figures (below)
- `notebooks/` – original analysis notebook
- `env/requirements.txt` – minimal deps

**Results (figures)**
- ![Year overview](results/figures/discharge_year_events.png)  
  *One-year discharge with detected storm “event” windows highlighted.*
- ![Fit comparison](results/figures/distfit_logdischarge_gamma_vs_normal.png)  
  *Log(discharge+1) with Normal vs Gamma fits (AICs in legend).*
- ![Rating curve](results/figures/rating_curve_powerlaw.png)  
  *Non-linear rating curve: gage height vs discharge.*
- ![Rolling annual total](results/figures/rolling_annual_total_discharge.png)  
  *Rolling 365-day total discharge (long-term variability).*
- ![Volatility view](results/figures/storm_spikes_percent_change.png)  
  *Daily %-change spikes over a six-month window.*