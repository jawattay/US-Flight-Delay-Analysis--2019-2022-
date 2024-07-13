![Photo](https://github.com/jawattay/US-Flight-Delay-Analysis--2019-2022-/blob/main/03%20-%20Visuals/pexels-joel-super-188959-2315265.jpg)

# CF-US-Flight-Delay-Analysis

Analyze effect of COVID-19 Pandemic on Domestic Flights in the United States.

## Objective

To build an interactive dashboard visually showcasing well-curated results of an advanced exploratory analysis conducted in Python.

## Data Source

This data set was sourced from Kaggle.com (https://www.kaggle.com/datasets/robikscube/flight-delay-dataset-20182022). The source of the raw data provided by the Kaggle.com user is from the Bureau of Transportation Statistics (link): https://www.transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=FGK&QO_fu146_anzr=b0-gvzr 

The Bureau of Transportation Statistics (BTS) is a federal agency within the United States Department of Transportation (DOT). Its primary role is to collect, analyze, and disseminate transportation-related data and statistics to support decision-making, policy development, and research within the transportation sector. BTS provides a wide range of information, including statistics on air, maritime, rail, and highway transportation, as well as on topics such as safety, energy, and the economy. The agency serves as a valuable resource for policymakers, researchers, businesses, and the general public interested in understanding various aspects of transportation in the United States.

This data set was selected because it contains tens of thousands of records of both geospatial, temporal, and continuous quantitative variables that can be utilized for the purposes of this achievement. I am also interested in the performance of different airlines and given the modern ease of access to airline travel as a means of relatively affordable domestic transportation in the United States. While there are certainly challenges, it is fascinating to me that airlines are able to accommodate large volumes of travelers. 

## Limitations

Analyzing flight data from 2018 to 2022 can offer valuable insights, but it comes with several limitations and ethical considerations.
1. Data Completeness and Accuracy:
- Not all airlines and airports may consistently report flight data.
- Data Errors: Mistakes in data entry or transmission can affect the accuracy of the analysis.
2. Data Standardization:
- Different Formats: Flight data from various sources may be in different formats, requiring extensive preprocessing to standardize.
- Varied Definitions: Terms and metrics (e.g., delays, cancellations) might be defined differently by different entities, complicating comparisons.
3. Temporal Changes:
- Pandemic Impact: The COVID-19 pandemic significantly disrupted air travel, making 2020-2021 data atypical. This period may not be representative of normal flight patterns and can skew trend analysis.
- Regulatory Changes: Changes in aviation regulations and policies over these years can affect flight operations and reporting.
4. Technological and Operational Changes:
- Improvements in Technology: Advances in aircraft technology and air traffic management systems can influence flight efficiency and safety, affecting trends over time.
- Operational Changes: Shifts in airline operations, such as route changes or fleet updates, can impact the data.
- Weather Events: Natural disasters and extreme weather can cause fluctuations in flight data, adding variability that might be hard to account for.
- Economic Factors: Economic conditions, fuel prices, and geopolitical events can also influence air travel patterns.

## Ethical Considerations

1. Privacy:
- Passenger Data: If the analysis involves detailed passenger information, it raises significant privacy issues. Ensuring anonymization and compliance with data protection laws is crucial. Care must be taken not to expose sensitive information that could identify individuals or proprietary airline operations.
2. Bias and Fairness:
- Bias in Data: The data might reflect inherent biases, such as socioeconomic disparities in travel patterns. Others need to be aware of these biases to avoid misleading conclusions.
- Equity Issues: The findings could impact policy decisions that may disproportionately affect certain groups, such as less affluent travelers or smaller regional airlines.
3. Transparency and Accountability:
- Methodology Disclosure: Clear documentation of data sources, methodologies, and assumptions is necessary to ensure the analysis can be scrutinized and replicated.
- Responsible Use: The results of the analysis should be used responsibly, avoiding sensationalism or misuse that could lead to public distrust or panic.
4. Impact on Stakeholders:
- Airline and Airport Operations: Findings might influence operational decisions, impacting employees and stakeholders. Analysts should consider the broader implications of their work.
- Public Perception: Misinterpretation of data can affect public confidence in air travel safety and reliability. Clear communication of findings and their limitations is essential.

## Questions Explored

- How has the total number of flights (domestic and international) changed from 2018 to 2022? What are the trends in passenger numbers over this period?
- What are the trends in on-time performance for flights over these years?
- Which airports and airlines have the highest and lowest rates of delays?
- How have flight cancellation rates changed over the years?
- What are the primary causes of cancellations during this period?
- Are there noticeable seasonal patterns in flight operations and delays?
- How do holiday seasons and major events affect flight performance?
- How did the COVID-19 pandemic impact flight volume and passenger numbers in 2020 and 2021 compared to 2018 and 2019?
- What recovery trends are observed in 2022?
- How did airlines and airports adjust their operations during the pandemic?
