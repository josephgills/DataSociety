# DataSociety
Author: Joe Gills

Date: 3/19/2024

## Prompt
Write a weather-forecasting application that takes geographic US latitude/longitude values as input and presents the weather from a point in time at the given location(s). Use a language and presentation method of your choice. The design of the application, as well as any additional information you’d like to display, is up to you. This application should:
- Accept geographic US latitude/longitude values as input
- For example: 38.2527° N, 85.7585° W
- Retrieve weather data using this free weather service: API Web Service (https://www.weather.gov/documentation/services-web-api&sa=D&source=calendar&ust=1641768438693965&usg=AOvVaw3OWCV8Z2DjkIpuF6eXz_L2)
- Present the “temperature” value for “Wednesday Night” at the input location

Your chosen tools will dictate your presentation method, but the key to this requirement is that the end-user receives the resulting forecast data. This could be done via a dynamic web page, command-line output, etc.
Along with the source code, include a README.md file in Markdown format which documents your solution and how to use it. Deliver the application via shared git repository (e.g. GitHub, BitBucket).

## Solution
This repo contains a python notebook that links to a Google Colab envirnoment. The notebook defines several functions that will retrieve temperature data for a given period and lat/lon position. The data is pulled from weather.gov using the api mentioned above.

## To Run
Follow the google colab link in the preview of the notebook or use this link https://colab.research.google.com/github/josephgills/DataSociety/blob/main/WeatherGrab.ipynb. Hit the play button and follow the prompt. After hitting the play button, you may be prompted to sign into your google account.
