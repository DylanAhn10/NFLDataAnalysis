# NFL Field Goal Analysis
This project uses NFL play-by-play data to explore field-goal accuracy and attempt volume from 2010 to 2025.
The notebook looks at:
- Kick distance and season trends
- Stadium roof and playing surface
- Temperature and wind
- Late-game field-goal attempts
## Notebook
The full analysis is in [`fieldgoals.ipynb`](fieldgoals.ipynb).
## Requirements
- Python 3
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- statsmodels
- pyarrow
- nfl_data_py
Install the required packages with:
```bash
pip install jupyter pandas numpy matplotlib seaborn scipy statsmodels pyarrow nfl_data_py
```
## Run the Project
Open the notebook and run the cells in order:
```bash
jupyter notebook fieldgoals.ipynb
```
The play-by-play data is downloaded through the `nfl_data_py` package.

