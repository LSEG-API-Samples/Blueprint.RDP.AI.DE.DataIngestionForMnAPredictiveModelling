# Data engineering - Data Ingestion for M&A predictive modelling


## <a id="overview"></a>Overview
This article focuses on the ingestion phase of an AI pipeline analysing corporate events. Corporate events, such as M&A or bankruptcy announcements, can result in substantial stock price changes. Academic research has shown evidence of significant abnormal returns for target company stocks, making target identification a perfect usecase for AI.

The final AI model, whose full implementation process can be found in our detailed article is a binary classifier between target and non-target companies. The feature space will therefore include the list of target and non-target companies along with a wide range of financial ratios such as profitability, liquidity, leverage of the businesses.

## <a id="disclaimer"></a>Disclaimer
The source code presented in this project has been written by Refinitiv only for the purpose of illustrating the concepts of creating example scenarios using the Refinitiv Data Library for Python.

***Note:** To [ask questions](https://community.developers.refinitiv.com/index.html) and benefit from the learning material, I recommend you to register on the [Refinitiv Developer Community](https://developers.refinitiv.com)*

## <a name="prerequisites"></a>Prerequisites

To execute any workbook, refer to the following:

- A Refinitiv Desktop license (Refinitiv Eikon or Refinitiv Workspace) that has API access 
- Tested with Python 3.7.13
- Packages: [plotly](https://pypi.org/project/plotly/), [scipy](https://pypi.org/project/scipy/), [statsmodels] (https://pypi.org/project/statsmodels/), [refinitiv.data](https://pypi.org/project/refinitiv-data/)
- RD Library for Python installation:  '**pip install refinitiv-data**'


  
## <a id="authors"></a>Authors
* **Haykaz Aramyan**
