# EfficientPortfolio_Optimization
Cloud Computing ETF (CLOU) by Global X Asset Management company has been evaluated in this exercise. ETF allocations are optimized, by maximizing the Sharpe Ratio and plotting efficient frontier for every week of the year

<b> Fund Summary (Source: Global X website) </b>

The Global X Cloud Computing ETF (CLOU) seeks to invest in companies positioned to benefit from the increased adoption of cloud computing technology, including companies whose principal business is in offering computing Software-as-a-Service (SaaS), Platform-as-a-Service (PaaS), Infrastructure-as-a-Service (IaaS), managed server storage space and data center real estate investment trusts, and/or cloud and edge computing infrastructure and hardware.

<b> Portfolio Optimization using EfficientFrontier </b>

Efficient Frontier is actually a plot of possible portfolios that can be built using different proportion of weights for each stock. Stretched on return and risk axes, efficient frontier shows all the portfolios that provide optmial level of return for a given level of risk. Any portfolio that is below the efficient frontier is Sub-Optimal, as for that similar level of risk greater return can be earned.

<b><i>1. Find the Companies that you want to include in your Portfolio </i></b>
 
In this case, we have chosen the companies that Global X Funds has included in its Cloud Computing ETF (CLOU)
 
<b><i>2. Find tickers of all the companies in the portfolio </i></b>
I removed some of the words from the Company's title to get the ticker symbols by scrapping the yahoo finance website.

Removed words {'INC', 'Holding',' CORP', 'INC-CL A', 'INC-CLASS A', 'LTD', 'GRP-ADR','-', 'CLASS', 'A','-CL A','INC-CLASS','CORP','INC-ADR','INC-CL','TRUST', 'CASH' }

CASH has been removed from the company's list
 
<b><i>3. From the tickers get the closing price for all the companies over the period of 2014-01-01 to 2019-07-15</i></b>
 
 Since for each week, weights of the companies are optimized, closing prices are calculated over each week
 
 <b><i>4. Formulate efficient frontier for each week and optimize weights by maximizing the sharpe ratio of the portfolio</i></b>

So, you can check for each week, what should have been the optimal weights of the companies. Future predictibility of weights is limited for this model. But the numbers can be used to compare with the weights of your ETF to get a sense of difference. Furthermore, machine learning techniques can be used to evaluate the patterns of difference between the values of this model and that of the ETFs


<b> Companies in the ETF </b>

COUPA SOFTWARE INC

SHOPIFY INC - CLASS A

XERO LTD

AKAMAI TECHNOLOGIES INC

ANAPLAN INC

DIGITAL REALTY TRUST INC

PAYCOM SOFTWARE INC

PROOFPOINT INC

PAYLOCITY HOLDING CORP

REALPAGE INC

SALESFORCE.COM INC

TWILIO INC - A

WORKDAY INC-CLASS A

DROPBOX INC-CLASS A

LOGMEIN INC

NETFLIX INC

CORNERSTONE ONDEMAND INC

QUALYS INC

ZSCALER INC

MICROSOFT CORP

BOX INC - CLASS A

MIMECAST LTD

EVERBRIDGE INC

AMAZON.COM INC

ALIBABA GRP-ADR

SPS COMMERCE INC

CYRUSONE INC

WORKIVA INC

ALPHABET INC-CL A

2U INC

CORESITE REALTY CORP

BENEFITFOCUS INC

21VIANET GROUP INC-ADR

QTS REALTY TRUST INC-CL A

IBM

KINGSOFT CORP LTD
