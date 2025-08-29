# weather_etl_pipeline
This is a live ETL pipeline project that demonstrates how to extract, tranform and load data

# Weather Data ETL Pipeline (Live Project)

This project demonstrates a live ETL (Extract, Transform, Load) pipeline using weather data from the OpenWeatherMap API for Hyderabad, India. The pipeline is implemented in a Jupyter Notebook and covers the following steps:

- **Extract:** Fetch weather forecast data from the OpenWeatherMap API.
- **Transform:** Clean, process, and visualize the data using Pandas, Matplotlib, and Seaborn.
- **Load:** Store the processed data into a PostgreSQL database.

## Features

- Live data extraction from OpenWeatherMap API
- Data cleaning and transformation
- Data visualization (line chart and heatmap)
- Loading data into a PostgreSQL database

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- requests
- matplotlib
- seaborn
- sqlalchemy
- psycopg2

Install dependencies with:

```bash
pip install pandas requests matplotlib seaborn sqlalchemy psycopg2-binary
```

## Usage

1. Clone this repository:

    ```bash
    git clone https://github.com/yourusername/weather-etl-pipeline.git
    cd weather-etl-pipeline
    ```

2. Open `script.ipynb` in Jupyter Notebook or VS Code.

3. Update your OpenWeatherMap API key and PostgreSQL credentials in the notebook.

4. Run all cells to execute the ETL pipeline.

## Notes

- **API Key:** You need a free API key from [OpenWeatherMap](https://openweathermap.org/api).
- **Database:** Ensure PostgreSQL is running and accessible with the credentials you provide.
- **Security:** Do not commit your real API keys or database passwords to public repositories.

## ETL Flow

```
Extract (API) → Transform (Pandas, Plots) → Load (PostgreSQL)
```

---

## License

This project is for educational purposes.
