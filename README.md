# Delhi-Weather-Analysis-for-the-year-2022
**--Introduction--**

Weather’s impacts are substantial and wide-reaching and occur on multiple temporal and spatial scales, so it becomes crucial to analyze the weather data whether to forecast or to understand the pattern of monsoons or factors like heatwaves affecting human life.

**--Problem aimed to solve--**

The aim of the project is to extract weather data from some reliable sources and to provide some useful insights regarding, India's capital Delhi, weather.

**--Data Description--**

Excel Files:1. This folder contains 12 different Excel .csv having the dataset of Delhi's weather for different consecutive months for the year 2022.
              2. This folder also contains the merged data in .csv as well as in .xls format for the year 2022.
Jupiter Notebook File: This folder contains the Python code which was used to scrap the data from the website(https://www.wunderground.com/)
PowerBi: This folder has the final Powerbi dashboard.

**--Methodology--**

The project involves extracting the data for Delhi for the year 2022 from January to December. After extracting the data, data was cleaned with the help of pandas and Excel, and useful insights were drawn with the help of Powerbi. The project aims to provide some useful insights and pattern findings to study the behavior of weather in Delhi.

**--Phases--**

1. Web Scraping: Collecting data from website(https://www.wunderground.com/) with the help of web scraping library like BeautifulSoup.

2. Data Cleaning: Removing irrelevant data and correcting inconsistencies, such as missing values, incorrect data types, or duplicate entries.

3. Data Transformation: Converting data into a format that is suitable for analysis, such as aggregating or summarizing data, or transforming data into a standard format.

4. Data Integration: Combining data from multiple sources/files to create a single dataset for analysis.

5. Data Analysis and Visualization: Create visualizations to explore/analyze the data and identify patterns or trends, and use them finally to create a dynamic dashboard with the help of power bi.

**--Web Scrapping--**

Here are some codes and visuals while scrapping the data.

![Screenshot 2023-07-09 185716](https://github.com/Ashish23-Karn/Delhi-Weather-Analysis-for-the-year-2022/assets/121361369/ca7b4011-f3d0-45a0-a601-047c5b3d85fe)

![Screenshot 2023-07-09 185729](https://github.com/Ashish23-Karn/Delhi-Weather-Analysis-for-the-year-2022/assets/121361369/b0a96de1-0e72-4ae3-b6ca-7a9e70bad714)

![Screenshot 2023-07-09 185748](https://github.com/Ashish23-Karn/Delhi-Weather-Analysis-for-the-year-2022/assets/121361369/2fa0966d-be39-4e03-9d19-f1382a4c0989)

**--Uncleaned data in Excel--**

![Screenshot 2023-07-09 200840](https://github.com/Ashish23-Karn/Delhi-Weather-Analysis-for-the-year-2022/assets/121361369/573fc5d7-4417-4219-b48e-430c95bcc6ba)

**--Cleaned data in Excel--**

![Screenshot 2023-07-10 012437](https://github.com/Ashish23-Karn/Delhi-Weather-Analysis-for-the-year-2022/assets/121361369/6fdaf553-7870-462d-bd2e-31e1b213d2d6)

**--Dashboard created--**

Here is the Powerbi dashboard which is dynamic in nature and the slicers added are for month and quarter.

![Screenshot 2023-07-10 013246](https://github.com/Ashish23-Karn/Delhi-Weather-Analysis-for-the-year-2022/assets/121361369/6061e171-81ef-4bf6-a09a-fcc58ea6e3df)
![Screenshot 2023-07-10 013308](https://github.com/Ashish23-Karn/Delhi-Weather-Analysis-for-the-year-2022/assets/121361369/1bb596f5-6919-4cce-84e0-583eaed699e0)

**--Insights--**

1.
![Screenshot 2023-07-10 013635](https://github.com/Ashish23-Karn/Delhi-Weather-Analysis-for-the-year-2022/assets/121361369/072da843-6411-48f0-a5a5-0c36b3f792d0)

Here is the variation of Temp throughout the year, one can see that the Max temperature was in May(45 Degree Celsius), whereas least temperature was in January/February (6 Degree Celsius).

2.
![Screenshot 2023-07-10 013731](https://github.com/Ashish23-Karn/Delhi-Weather-Analysis-for-the-year-2022/assets/121361369/867e8749-6b80-44ab-a275-3420afb2c8fc)

Here is the max. variation of all factors (temperature, wind speed, humidity, and precipitation), there is sudden growth for quarter 3 in terms of precipitation, as we know this is the monsoon season in Delhi.

3.
![Screenshot 2023-07-10 013750](https://github.com/Ashish23-Karn/Delhi-Weather-Analysis-for-the-year-2022/assets/121361369/ced3830f-5705-4124-9c03-f3721adef61f)

Here is the precipitation and humidity variation for all months, January was the most humid month whereas there was the most rain in July. 

4.
![Screenshot 2023-07-10 013813](https://github.com/Ashish23-Karn/Delhi-Weather-Analysis-for-the-year-2022/assets/121361369/3c0d60a9-0edc-4eff-9298-851e2a09490b)
![Screenshot 2023-07-10 013901](https://github.com/Ashish23-Karn/Delhi-Weather-Analysis-for-the-year-2022/assets/121361369/1651b8c2-893f-49e3-9ee7-0e4dbee3fe86)

In pic_1, this is the visual for total precipitation/rain throughout the year, whereas in pic_2, this is the average temperature for Delhi throughout the year 2022.

5.
![Screenshot 2023-07-10 013839](https://github.com/Ashish23-Karn/Delhi-Weather-Analysis-for-the-year-2022/assets/121361369/81ea57c3-0a6a-43bb-a41b-164b9d76b25e)

Here is the variation of perception for average values of different factors like avg wind speed, avg temperature, etc.

**--Challenges and learnings--**

1. The main challenge posed by this project was to extract the data from reliable sources as most of the sources was having forecast values but few have historical data for the weather.
2. The other challenge posed was to extract the data with the help of beautiful soup as the data was in table format where the values and header were having the same class.
3. Another challenge was to clean the data, for that Excel was used which was more handful as the data were limited.

--Overall, The project can serve as a valuable resource for policymakers, and the general public interested in gaining insights about historical weather pattern for the city.






















































