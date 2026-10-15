# delta_hedging_simulation
A Python simulation made to serve as a final project for Numerical Methods in Finance course at the Jagiellonian University in Krakow. It is a Jupyter notebook showcasing methods for simulating stock prices, solving the Black-Scholes PDE for options and analysing the delta hedging strategy on a simulated portfolio.

### View the notebook
See the fully evaluated HTML version of the notebook in `Delta_hedging.html`.  
For the option to modify and run the notebook's contents, clone this repository and run
```bash
pip install -r requirements.txt
jupyter notebook Delta_hedging.ipynb
```

## Sample results
Call option value diffussion  
<img src="plots/european_call_diffusion.png" alt="Call option value diffussion" width="800">
  

Put option final value from numerical calculation vs analytical  
<img src="plots/final_solution_put.png" alt="Put option final value" width="800">

Hedged vs unhedged P&L distribution  
<img src="plots/hedged_unhedged_distribution.png" alt="P&L distribution" width="800">

Hedging results for different rebalancing frequencies  
<img src="plots/frequencies_comparison.png" alt="Rebalancing frequencies dashboard" width="800">

Hedging results for different market conditions  
<img src="plots/market_conditions_comparison.png" alt="Market conditions dashboard" width="800">

Error accumulation for different frequencies  
<img src="plots/error_accumulation.png" alt="Error accumulation" width="800">

### Acknowledgements
Parts of the project made in collaboration with Arnold Voicinovič [[GitHub](https://github.com/arni-v)]
