# Corporate_ESG_Metrics_Analysis

Personal Project: Creating a visual representation of data via Tableau to allow stakeholders and/or non-technical audiences to examine ESG attributes and indicators from over 15,000 companies, as reported by MSCI. MSCI ESG Ratings are used to measure a company's management of financially relevant ESG risks and opportunities. They are one of the leading providers of ESG-related data for the global investment community.

ESG stands for Environmental, Social, and Governance and is term used often in the corporate space to set a standard of impact that companies can adhere to. ESG is an up-and-coming criteria that many companies are using for investing and screening. For many companies with documented ESG strategies, it is critical to assess and adhere to ESG ratings/scores for compliance purposes. 

MSCI rates ESG with letters: ranging from leader (AAA, AA), average (A, BBB, BB) to laggard (B, CCC). 

As more companies begin to see ESG standards/going green as a profitable business strategy, many are also using methods of greenwashing and other deceptive advertising to mask their impact on the environmental, society, and policy. Methods of this include: use of environmental imagery, suspicious claims lacking evidence, and rebranding.

As a consumer and data analyst by nature, it is important for me to not only analyze sustainability reports that companies produce but to also cross-check this with data from external sources, such as MSCI. That is because companies will always pursue their own best interests. Thus, I was eager to explore this very large dataset further and distinguish patterns that would otherwise get looked over easily. In this best interest of stakeholders e.g. investors and consumers, I produced this data analysis and visualization to convey the patterns that would have otherwise been overlooked with this data.

To learn more about MSCI, please visit the following link: https://www.msci.com/who-we-are/about-us


### Tools:
Jupyter Notebook, Tableau Software

### Language:
Python, SQL

### Libraries:
pandas, numpy

### Database:

PostgreSQL/pgAdmin4

### Dataset:
https://www.kaggle.com/datasets/debashish311601/esg-scores-and-ratings


## Visual Representation of Data via Tableau

https://public.tableau.com/app/profile/katherine.marcinkowski/viz/ESGCompanyDataBreakdown/ESGDataBreakdown?publish=yes

Utilized Tableau Software to create dynamic visual representations of the data to showcase various ESG attributes and higlight any potential patterns hidden within the data.


a. Average Overall ESG Score by Country Appearance: The US, Japan, and Canada appeared to be the countries most represented by the companies in the dataset. The US exceeds the latter by almost 3x the amount of appearances. The average overall ESG score for each country is listed next to its corresponding bar in the graph.

<img src="https://github.com/katmarcin/Corporate_ESG_Metrics_Analysis/blob/3706cdec152c642975651b6aa18e56eff9846cf5/images/country_esg.jpg" width="680" height="440" />

b. Sector Breakdown by Size: Banks, Utilies, and Real Estate Management & Services represent a large portion of the dataset. Corresponding average overall ESG scores for each sector are lsited adjacent to each bar in the graph.

<img src="https://github.com/katmarcin/Corporate_ESG_Metrics_Analysis/blob/3706cdec152c642975651b6aa18e56eff9846cf5/images/sector.jpg" width="680" height="440" />

c. Treemap: Overall ESG Rating. The following spread highlights the proportions of each rating relative to each other within the entire dataset. The more common the rating, the larger the box. 'A' and 'BBB' are the two most common overall ratings seen across all industries.

<img src="https://github.com/katmarcin/Corporate_ESG_Metrics_Analysis/blob/3706cdec152c642975651b6aa18e56eff9846cf5/images/treemap.jpg" width="680" height="440" />

## Data Mining / Cleaning the Data with Python

Data mining and cleaning is performed within Jupyter Notebook using Python coupled with pandas and numpy libraries. 

## Descriptive Statistics via Microsoft Excel / Excel VBA



## Database Creation via PostgreSQL/pgadmin4


Applied data engineering concepts to create a database in PostgreSQL/pgadmin4. Data analysis is performed on the cleaned CSV file exported from Jupyter.

a.  List of US companies with highest overall esg rating (AAA) and score (10).
* Some familiar names from this list include Adobe Inc, Best Buy Co Inc, Hasbro Inc, and Kellogg Company.

<img src="https://github.com/katmarcin/Corporate_ESG_Metrics_Analysis/blob/874f4b25d984309096ef589f172ba836eb7a85a3/images/sql_queries/us_aaa_10.jpg" />

b.  List of US companies in the 'Household & Personal Products' sector in the 'CCC' category
* The two companeis that appear within this sector, with the worst score is Revlon Inc and Reynolds Consumer Products. Revlon is widely known for carrying cosmetics and other personal care products. Reynolds Consumer Products' name can be recognized on household items such as aluminum foil "Reynolds Wrap" and another brand it carries "Hefty" for food and storage bags.
* When you visit the company's website, the first thing you may notice on the header is the 'sustainability' tab.

https://www.reynoldsconsumerproducts.com/sustainability

<img src="https://github.com/katmarcin/Corporate_ESG_Metrics_Analysis/blob/874f4b25d984309096ef589f172ba836eb7a85a3/images/sql_queries/hpp_ccc.jpg" />


c.  List of US companies by sector ascending in the 'CCC' category
  * Example of a new household name "Peloton" appears in the data. The company appears to have a poor ESG and rating.

<img src="https://github.com/katmarcin/Corporate_ESG_Metrics_Analysis/blob/874f4b25d984309096ef589f172ba836eb7a85a3/images/sql_queries/sector_asc_ccc.jpg" />

 * insert in contrast to sustainability marketing etc...

d.  Ascending list of distinct industry sectors in the dataset

<img src="https://github.com/katmarcin/Corporate_ESG_Metrics_Analysis/blob/874f4b25d984309096ef589f172ba836eb7a85a3/images/sql_queries/sectors.jpg" />


e.  US ESG 'Leaders' 

<img src="https://github.com/katmarcin/Corporate_ESG_Metrics_Analysis/blob/874f4b25d984309096ef589f172ba836eb7a85a3/images/sql_queries/us_leaders.jpg" />


f.  US ESG 'Leaders' Count

<img src="https://github.com/katmarcin/Corporate_ESG_Metrics_Analysis/blob/874f4b25d984309096ef589f172ba836eb7a85a3/images/sql_queries/count_us_leaders.jpg" />


g.  US ESG 'Average' Companies

<img src="https://github.com/katmarcin/Corporate_ESG_Metrics_Analysis/blob/874f4b25d984309096ef589f172ba836eb7a85a3/images/sql_queries/average_comps.jpg" />


h.  US ESG 'Average' Companies Count

<img src="https://github.com/katmarcin/Corporate_ESG_Metrics_Analysis/blob/874f4b25d984309096ef589f172ba836eb7a85a3/images/sql_queries/average_comps_count.jpg" />

i.  US ESG 'Laggards' Count

<img src="https://github.com/katmarcin/Corporate_ESG_Metrics_Analysis/blob/874f4b25d984309096ef589f172ba836eb7a85a3/images/sql_queries/us_laggards_count.jpg" />



