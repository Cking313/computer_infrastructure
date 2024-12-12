# Computer Infrastructure

This repository contains the results of tasks for the Computer Infrastructure module - the summary of tasks performed, and exploration and summarisation of weather data can be found in the accompanying Jupyter notebook - `weather.ipynb`. 

The `weather.sh` script retrieves weather data from the Athenry weather station in JSON format and saves it to the `data/weather` directory with the current timestamp formatted as its filename. This script runs every morning at 10am via the Github action defined in `.github/workflows/weather-data.yml` - this automatically commits the latest weather to the repository.
