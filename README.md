# Flarient Research Notebooks

Reproducible Jupyter notebooks for space weather research using Flarient data. Clone, run, and discover the Flarient platform.

## Notebooks

| Notebook | Description |
|----------|-------------|
| [01_predicting_geomagnetic_storms.ipynb](notebooks/01_predicting_geomagnetic_storms.ipynb) | Predicting geomagnetic storms with Flarient data |
| [02_kp_forecast_calibration.ipynb](notebooks/02_kp_forecast_calibration.ipynb) | Analysing Kp forecast calibration |
| [03_solar_wind_vs_geomagnetic.ipynb](notebooks/03_solar_wind_vs_geomagnetic.ipynb) | Solar wind versus geomagnetic response |
| [04_aurora_probability_calibration.ipynb](notebooks/04_aurora_probability_calibration.ipynb) | Aurora probability calibration |
| [05_human_vs_ai_forecasting.ipynb](notebooks/05_human_vs_ai_forecasting.ipynb) | Human vs AI forecasting accuracy |
| [06_near_earth_asteroids.ipynb](notebooks/06_near_earth_asteroids.ipynb) | Near-Earth asteroid approaches |

## Quick start

\`\`\`bash
git clone https://github.com/flarientglobal/flarient-notebooks.git
cd flarient-notebooks
pip install -r requirements.txt
jupyter notebook
\`\`\`

Each notebook is self-contained and uses public data from:
- [NOAA SWPC](https://www.swpc.noaa.gov/) — space weather data
- [NASA NeoWS](https://api.nasa.gov/) — near-Earth objects
- [Flarient API](https://flarient.com/api-docs) — forecasts and events

## About

Built by [Flarient](https://flarient.com) — the space weather intelligence platform. Part of the [Flarient Constellation](https://github.com/flarientglobal/flarient-constellation).

## License

MIT — notebooks are open source and free to use for research.
