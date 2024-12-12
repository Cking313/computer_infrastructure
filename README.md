# Computer Infrastructure

This repository contains the results of tasks for the COmputer Infrastructure module - the summary of tasks performed, and exploration and summarisation of weather data can be found in the accompanying jupyter notebook - `weather.ipynb`. 

The `weather.sh` script retrieves weather data from the Athenry weather station in json format and saves it to the `data/weather` directory with the current timestamp formatted as its filename. This script runs every morning at 10am via the github action defined in `.github/workflows/weather-data.yml` - this automatically commits the latest weather to the repository.