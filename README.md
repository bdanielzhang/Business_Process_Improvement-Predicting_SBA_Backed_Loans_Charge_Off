#**Business Process Improvement: SBA Loan Charge-Off Analysis**
BA810: Supervised Machine Learning
<br>
Professor Nachiketa Sahoo
<br>
Cohort B Team 13
<br>
Team Members: Boyuan (Daniel) Zhang, Yutao (Peter) Luo, Yen-Chun (Albert) Chen, Xinyuan (Klaus) Xu
***

##**1. Problem Definition**
###**1.1 Background Information**

According to the annual report from the United States Census Bureau, **Small Business Administration (SBA)** classifies small businesses as entities with annual revenue ranging from \$1 million to \$40 million, and a number of hired employees ranging from 100 to over 1,500. Additionally, there are 32.5 million small businesses in the US, and the number is quickly growing in the nowadays post-pandemic time. Based on the public information on SBA official website, small business owners apply for loans through banks or credit unions (lending partners) to advance their business, and the lending partners then apply to SBA for a loan guarantee. Therefore, in case of loans defaulting for various reasons, the SBA will pay back their partners instead of letting them be exposed to such defaulting risk.

###**1.2 Project Goal**
Based on a survey done by the Federal Reserve Bank, 54% of US small businesses applied for a loan or a line of credit in 2018. According to Kevin Voigt and Caren Weiner Campbell's article on nerdwallet, 17.4% of SBA-guaranteed loans from 2006 to 2015 went to default. Therefore, in our project, we aim at improving the process of loan lending from SBA's perspective. We try to build predictive models using variables that a lending partners might need to provide to the SBA about the businesses themselves. **Our goal is to predict whether a SBA-backed loan to a US small business will be paid in full or charged-off using selected data, compare prediction results across different models, and make recommendations to the SBA about updating their existing model on choosing which loans to guarantee on.**

###**1.3 Intended Audience**
The audience who place the most significant value on this analysis should be the SBA. Although we are aware that SBA probably have certain predictive models that detect whether an outgoing loan is going to default, we are trying to build models that could potentially be used in **both government entities and commerical banks**, or any entity that has a lending process with data gathering capabilities.
***
