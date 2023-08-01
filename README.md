# Phoenix Climate Data

This Jupyter notebook explores climate trends for the city of Phoenix, Arizona since 1970, specifically:

* The average annual summer temperature from June to August
* The number of days over 100 °F and 110 °F for each year
* The maximum number of consecutive days over 110 °F for each year
* Annual precipitation

The data is obtained from the [NCEI Data Service API](https://www.ncei.noaa.gov/support/access-data-service-api-user-documentation).

## Installation

This project requires [Jupyter](https://jupyter.org/install) and the following Python libraries, which can be installed with [pip](https://pypi.org/project/pip/) or [conda](https://docs.conda.io/en/latest/) if they are not pre-installed:
* pandas
* matplotlib
* seaborn


## Usage
From the command line, run the following command:

`jupyter notebook phoenix_climate_trends.ipynb`

## Sample Output
![A matplotlib figure consisting of Phoenix climate trends represented by different subplots](PhoenixWeatherTrends.png)

## License

[MIT](https://choosealicense.com/licenses/mit/)
