# Real-world Data Wrangling
In this project, I applied the skills I acquired in the course to gather and wrangle real-world data with two datasets of my choice.
I retrieved and extracted the data, assessed the data programmatically and visually, across elements of data quality and structure, and implemented a cleaning strategy for the data. I then stored the updated data into a data store, combined the data, and answered a research question with the datasets.

I explored the companies that IPO'd in the record breaking year of 2021. About 1053 companies IPO'd that year, which was a jump from the 480 of the previous year, also a record year. I used kaggles [company ipos (2019 - 2021)](https://www.kaggle.com/datasets/shivamb/company-ipos-2019-2021) dataset. Additionally, I collected more variables from the source of kaggles dataset, [Stock Analysis](https://stockanalysis.com/). Specifically, I looked at the relationship between SPAC and non SPAC IPOs and how they compare and contrast on multiple spectrums.

#### **Dataset 1**

Type: CSV File.

Method: This data, called company ipos (2019-2021), was downloaded programmatically using `opendatasets` from kaggle and saved as a csv file. I want to specifically focus on the year 2021 which was a record breaking year in terms of number of IPOs.

Dataset variables:

*   *ID: Row ID.*
*   *IPO Date: The month, day, and year the company IPO'd.*
*   *Symbol: The company's ticker symbol on the exchange.*
*   *Company Name: Name of IPO company.*
*   *IPO Price: The price set at the companies IPO.*
*   *Current: The current price.*
*   *Return: Return from set price to current price.*

#### Dataset 2

Type: CSV File.

Method: This data was downloaded manually from Stock Analysis, a website that collect company IPO data. This is also the source of the kaggle dataset. Here we have access to more variables that could be useful for our analysis.

Dataset variables:

*   *IPO Month: The month company IPO'd.*
*   *IPO Day: The day the company IPO'd.*
*   *IPO Year: The year the company IPO'd.*
*   *Symbol: The company's ticker symbol on the exchange.*
*   *Founded: The year company was founded.*
*   *Industry_Sector: The industry and sector the company is in.*
*   *is SPAC: Was the IPO a special purpose acquisition?*
