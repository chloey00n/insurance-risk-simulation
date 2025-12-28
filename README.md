# Monte Carlo Insurance Decision Simulation

This repository contains a reproducible **Monte Carlo simulation model built from scratch in Python**.

## Summary

Based on a Monte Carlo simulation of 50,000 trials over a 5-year period,  
HIC (Hawthorne Insurance Corporation) provides the lowest expected total cost  
and acceptable tail risk (P95 and P99) compared to RCNC1, RCNC2, and CTC.

- Expected 5-year cost: lowest among all plans  
- Risk coverage: pays all fleet losses above \$24M per year  
- Rebate: 3.5% of insurer profits reduces net expected cost  
- Sensitivity (25% safer): ranking remains the same — HIC still best  

Recommendation: Ontario Gateway should select the HIC plan for its 5-year aircraft insurance policy,  
as it offers the best balance of cost efficiency and risk protection.

## Recommendation

Ontario Gateway should adopt the HIC insurance policy  
for its 5-year aircraft coverage, as it delivers  
the best trade-off between premium cost, loss protection, and financial stability.

## What’s inside

- `notebooks/02_ontario_gateway_simulation.ipynb`: final, polished analysis notebook (run this)
- `notebooks/01_original_submission.ipynb`: original submission snapshot (optional reference)
- `src/ontario_gateway/`: optional space to refactor notebook logic into reusable modules

## How to run

```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .\.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

Then open and **Run All**:
- `notebooks/02_ontario_gateway_simulation.ipynb`

## Notes

- No external datasets are required; the simulation is parameterized directly in the notebook.
- Random seed is fixed for reproducibility.

