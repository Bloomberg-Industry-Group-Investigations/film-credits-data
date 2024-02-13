# Bloomberg Industry Group Investigations - Film Tax Incentives Data

## Terms of Use
By downloading this Dataset, you agree that you will attribute the Dataset and any use of the Dataset to Bloomberg Industry Group and/or Bloomberg Tax. You may use the Dataset for personal or internal business purposes, and may make limited use of the Dataset in connection with the provision of other services to clients; provided that you may not monetize the Dataset or otherwise make commercial use of the Dataset where the Dataset constitutes all, or substantially all, of the commercial offering. The Dataset is provided "as-is" and without any express or implied warranties.

### Attribution
The provided data in the folder titled ["raw"](data/raw/) should be cited as "[Source Agency's Name] obtained by Bloomberg Tax." If the data is used in an online story, the source line should include a link to this repository.

The structured data we compiled and that is found in the folder titled ["created"](data/created/) should be cited using the appropriate description preceded by “Bloomberg Tax analysis of.” For example, "Bloomberg Tax analysis of [Source Agency's Name] records."

## Introduction

This repository contains the documents and spreadsheets detailing film tax incentives that were used to produce the story ["How a Bad Bunny Beer Ad Got Puerto Rico Tax Money to Shoot in LA,"](https://news.bloombergtax.com/daily-tax-report/how-a-bad-bunny-beer-ad-got-puerto-rico-tax-money-to-shoot-in-la) which was published on Feb. 5, 2024.

Twenty-nine states and territories offering film tax credit programs allow incentives for commercial production. Major companies, including McDonald’s Corp., Kellanova, and AbbVie Inc., receive these tax credits to promote products such as chicken, cereals, and prescription drugs. Tax credits are sometimes obtained through ad agencies, while in other cases, companies directly get the credits directly. Certain states allow recipients with minimal or no tax obligations to sell these credits for cash, enabling heavy buyers like Walmart Inc., Apple Inc., and Bank of America Corp. to reduce their state tax liabilities, despite having no involvement in the production.

## Methodology

The data originates from information requests sent to tax departments and state economic development agencies between September 2023 and January 2024. The data covers time periods ranging from 2019 to 2023.

The information requests focused on obtaining data related to film tax credits, including details on credits issued, the companies receiving the credits, the monetary investments made in direct and post-production expenditures, and individuals and businesses purchasing the credits along with the price paid.

Bloomberg Tax requested records of tax-credit recipients and buyers in all 15 jurisdictions that allow transfers. Only Illinois provided a comprehensive list. The rest provided partial information or didn’t respond or denied the requests citing taxpayer confidentiality. 

### List of Data and Documents by State

Documents and spreadsheets are organized by state and further broken down into two categories: the **raw** data as received and **created** data that cleaned or summarized the raw data. The full listing can be found below.

#### Georgia
- *Raw Data:*
  - [FY20_report.pdf](data/raw/georgia/FY20_report.pdf): Summary of film tax credits granted by category for the 2020 fiscal year. Obtained via public records request from the Georgia Department of Economic Development.
  - [FY21_report.pdf](data/raw/georgia/FY21_report.pdf): Summary of film tax credits granted by category for the 2021 fiscal year. Obtained via public records request from the Georgia Department of Economic Development.
  - [FY22_report.pdf](data/raw/georgia/FY22_report.pdf): Summary of film tax credits granted by category for the 2022 fiscal year. Obtained via public records request from the Georgia Department of Economic Development.
  - [FY23_report.pdf](data/raw/georgia/FY23_report.pdf): Summary of film tax credits granted by category for the 2023 fiscal year. Obtained via public records request from the Georgia Department of Economic Development.

- *Created Data:*
  - [georgia_films_summary.xlsx](data/created/georgia/georgia_films_summary.xlsx): Spreadsheet containing information on the amount of film tax credits granted by category. The information was obtained from the above PDF reports published by the Georgia Department of Economic Development.


#### Illinois
- *Raw Data:*
  - [illinois_foia_pt_1.xlsx](data/raw/illinois/illinois_foia_pt_1.xlsx): Data showing recipients and buyers of film tax credits. Obtained via public records request from the Illinois Department of Commerce & Economic Opportunity.
  - [illinois_foia_pt_2.xlsx](data/raw/illinois/illinois_foia_pt_2.xlsx): Data showing film tax credits broken down by category. Obtained via public records request from the Illinois Department of Commerce & Economic Opportunity.

- *Created Data:*
  - [illinois_foia_cleaned.xlsx](data/created/illinois/illinois_foia_cleaned.xlsx): Cleaned version of the above film tax credit data published by the Illinois Department of Commerce & Economic Opportunity. The original document presented inconsistencies in company names, including variations in punctuation and capitalization. We standardized the names of these companies to better analyze the information provided. 


#### New Jersey
- *Raw Data:*
  - [new_jersey_credit_transfers.xlsx](data/raw/new_jersey/new_jersey_credit_transfers.xlsx): Film tax credit purchaser data. Obtained via public records request from the New Jersey Economic Development Authority.


#### Puerto Rico
- *Raw Data:*
  - [puerto_rico_act_60_tax_credits_table.xlsx](data/raw/puerto_rico/puerto_rico_act_60_tax_credits_table.xlsx): Data showing the film tax credits awarded and total investment, including jobs, as reported by companies. Obtained via public records request from the Departamento de Desarrollo Económico y Comercio.
  - [puerto_rico_film_tax_credit_transfers.pdf](data/raw/puerto_rico/puerto_rico_film_tax_credit_transfers.pdf): Anonymized data on the sale of film tax credits (buyers' names are obscured). Obtained via public records request from the Departamento de Desarrollo Económico y Comercio.
