# Impact of the Food Industry on the Environment and its Ecosystems

This project explores the environmental repercussions of the food industry and agriculture, focusing on factors like greenhouse gas emissions, water wastage, and food waste. By analyzing global datasets from 2010 to 2020, the study aims to highlight the severity of these impacts and emphasize the need for sustainable practices in the food sector—one of the world's leading polluting industries.

**Course:** AIS (Data Analysis in Big Data Systems)

## Architecture

<p align="center">
  <img src="https://github.com/CatarinaCosta02/AIS/blob/main/graphs/Architecture.png" width="600">
</p>

## Techn Stack

- **Language:** Python
- **Environment Management:** miniconda
- **Data Processing:** Jupyter Notebooks, Pandas, and PySpark
- **Database:** Apache Cassandra
- **Visualization:** Power BI

## Data Visualization

Using Power BI, dynamic dashboards to identify trends such as:
- Global emissions of $CO_2$, $CH_4$ e $N_2O$
- Top 10 countries by food gas emissions (e.g., Nigeria, Ethiopia, Indonesia)
- Relationship between crop residues and $CO_2$ emissions

## Datasets

- [Agrofood co2 emission.csv](https://www.kaggle.com/datasets/alessandrolobello/agri-food-co2-emission-dataset-forecasting-ml)
- [Total Emissions Per Country (2000-2020).csv](https://www.kaggle.com/datasets/justin2028/total-emissions-per-country-2000-2020)
- [global-food.csv](https://ourworldindata.org/explorers/global-food?tab=table&Food=Maize+%28corn%29&Metric=Production&Per+capita=false&country=OWID_WRL~USA~CHN~IND~BRA~GBR)
- [fao global food waste 2000 2021.csv](https://www.kaggle.com/datasets/timileyinoladayo/fao-global-food-loss-2000-to-2021/data?select=FAO_food_loss_2000_2021.csv)


## Repository Structure

| Folder/File | Description |
| :--- | :--- |
| `Documents` | Final report, Scientific_Article and Powerpoint presentation|
| `dataframes` | Intermediate processed dataframes ready for database ingestion |
| `datasets` |Raw datasets sources from Kaggle and Our World In Data|
| `graphs` | PowerBI graphs|
| `parquet_format` | Optimized data storage: Small parquet_format files used to insert into Cassandra database |
| `ais.ipynb` | JupyterLab notebook where all the data exploration, preparation, and insertion into the Apache Cassandra database is represented |
| `cassandra_to_powerbi.txt` | Instructions to connect Cassandra database to Power BI |


## Team

Catarina Costa, pg52676

Marta Aguiar, pg52694 
