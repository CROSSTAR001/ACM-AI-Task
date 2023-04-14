# ACM-AI-Task
 To build a simple deep learning model with the dataset provided - (Air Quality Annual Summary)[https://www.kaggle.com/datasets/epa/air-quality]

## Deliverables:

### **1. Theoretical analysis of the dataset provided**

The **Air Quality Annual Summary** dataset contains information about air quality measures taken from monitoring stations across the United States. The data is provided by the **U.S. Environmental Protection Agency** and covers a period of several years.

The dataset contains 55 columns and over 1.04 million rows of data. The columns include information about the location of the monitoring station, the type of pollutant being measured, and the results of the measurements taken. Some of the most important columns for analysis might include the *pollutant_standard*, *metric_used*, *method_name*, *arithmetic_mean*, and *arithmetic_standard_dev* columns.

With this dataset, it is possible to conduct a wide range of analyses related to air quality. For example, it might be possible to explore trends in air quality over time, to identify regions or cities with particularly high levels of pollution, or to investigate the impact of specific pollutants on human health.

One potential challenge with the dataset is that it is quite large and contains a lot of information. This means that any analysis will need to carefully consider which columns are most relevant to the research question at hand. It may also be necessary to conduct some data cleaning and processing to ensure that the data is in a suitable format for analysis.

Overall, the Air Quality Annual Summary dataset is a rich resource for anyone interested in studying air quality in the United States. With careful analysis, it is possible to uncover important insights about pollution trends, human health impacts, and more.

### **2. Details on what your model will predict**

The **Air Quality Annual Summary** dataset contains information on various parameters related to air quality. My model will be predicting the impact of air pollution on human health. I have used 6 featues including **Arithmetic mean**, **Pollutant standard**, **Observation count and percent**, **Year**, and **Location**. 

**Parameter name**: This column indicates the type of pollutant being measured, which is important in assessing its impact on health. For example, pollutants such as ozone, particulate matter, and sulfur dioxide are known to have negative health effects.

**Arithmetic mean**: This column provides an average value of the pollutant concentration over a given period. High levels of pollutants, as indicated by high arithmetic mean values, are likely to have a greater impact on human health.

**Pollutant standard**: This column indicates whether a pollutant concentration exceeds the standard set by the EPA for human health. A pollutant that exceeds the standard is likely to have negative health effects.

**Year**: This column indicates the year of measurement, and can be used to track trends in pollution over time.

**Observation count and percent**: These columns indicate how many observations were taken and what percentage of those observations were valid. This can provide an indication of the reliability of the data and the level of confidence in the results.

**Location columns**: Latitude, longitude, state code, county code, and city name columns can help in identifying the areas with the highest pollution levels, which can be useful in targeting interventions and policy decisions.


By analyzing this data, it is possible to predict the potential health risks associated with exposure to different levels of air pollutants. For example, high levels of certain pollutants may lead to *respiratory problems*, *heart disease*, or other health issues. By understanding how these pollutants affect human health, policymakers can make informed decisions about how to mitigate the impact of air pollution on their communities.
