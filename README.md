# Bayesian Network software review in R enviroment

In this repository, you will find a software review about the most popular R packages to deal with Bayesian Network modeling. By performing an exhaustive examination of the users and functions manuals from the considered packages an overview regarding their functionalities, approaches, methods, algorithms, limitations, and added value, among others, is provided. Also, each of these packages was tested in the R environment using standards datasets to assess the points mentioned above.

Using this information, a set of tables were built to guide the users about which package they can work with considering the characteristics of the dataset they have available, the work that they want to perform, the presence of missing data, and the type of data, among others. Likewise, another set of tables are provided that serve as an inventory of the algorithms, methods, scores, independence test and others, implemented in each package.

According to the task that they tackle in the modeling process, the packages can be classified into two main categories, which are not mutually exclusive, namely: learning (structure and parameters) and inference. In total nine packages were analyzed, the following ones can be used to learn the structure and parameters of the Bayesian Network: **catnet** (Balov y Salzman, 2020), **sparsebn** (Aragam, Gu y Zhou, 2019), **pcalg** (Kalisch, et al. 2014), **deal** (Boettcher y Dethlefsen, 2003), **bnclassify** (Mihaljevic, Bielza y Larrañaga, 2018), **bnstruct** (Sambo y Franzini, 2019) and **bnlearn** (Scutari, 2010). **bnclassify** is a special case due to it allows to build a Bayesian Network classifier. Regarding the inferece process, the examined packages were: **gRain** (Højsgaard, 2012), **BayesNetBP** (Yu, Moharil y Blair, 2019), **bnstruct** (Sambo y Franzini, 2019) and **bnlearn** (Scutari, 2010); the latter two can perform both tasks but the main goal that they seek is the structure and parameter learning.


| Package | Version | Publication Year | Actual Version Year | Historical Downloads* | Semiannual Downloads**|
| --- | --- | --- | --- | --- | --- |
| catnet | 1.15.7 | 2010 | 2020 | 49,603 | 6,858 |
| sparsebn | 0.1.0 | 2016 | 2019 | 12,116 | 3,179 |
| pcalg | 2.6.10 | 2006 | 2020 | 89,004 | 13,598 |
| deal | 1.2.39 | 2002	| 2018 | 53,857 | 6,358 |
| bnclassify | 0.4.5 | 2015 | 2020 | 27,325 | 5,528 |
| bnstruct | 1.0.6 | 2016 | 2019 | 27,226 | 4,717 |
| bnlearn | 4.5 | 2007 | 2019 | 259,676 | 40,783 |
| gRain | 1.3.4 | 2008 | 2020 | 114,351 | 22,196 |
| BayesNetBP | 1.4.0 | 2017 | 2018 | 13,833 |	3,106 |

Note : The downloads were obtained using R **cranlogs** package

* from October 2012 until March 2020

** from October 2019 until March 2020



