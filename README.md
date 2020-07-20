# Bayesian Network software review in R environment
-----

In this repository, you will find a software review about the most popular R packages to deal with Bayesian Network modeling. By performing an exhaustive examination of the users and functions manuals from the considered packages an overview regarding their functionalities, approaches, methods, algorithms, limitations, and added value, among others, is provided. Also, each of these packages was tested in the R environment using standards datasets to assess the points mentioned above.

Using this information, a set of tables were built to guide the users about which package they can work with considering the characteristics of the dataset they have available, the work that they want to perform, the presence of missing data, and the type of data, among others. Likewise, another set of tables are provided that serve as an inventory of the algorithms, methods, scores, independence test and others, implemented in each package.

According to the task that they tackle in the modeling process, the packages can be classified into two main categories, which are not mutually exclusive, namely: learning (structure and parameters) and inference. In total nine packages were analyzed, the following ones can be used to learn the structure and parameters of the Bayesian Network: **catnet** (Balov y Salzman, 2020), **sparsebn** (Aragam, Gu y Zhou, 2019), **pcalg** (Kalisch, et al. 2014), **deal** (Boettcher y Dethlefsen, 2003), **bnclassify** (Mihaljevic, Bielza y Larrañaga, 2018), **bnstruct** (Sambo y Franzini, 2019) and **bnlearn** (Scutari, 2010). **bnclassify** is a special case due to it allows to build a Bayesian Network classifier. Regarding the inferece process, the examined packages were: **gRain** (Højsgaard, 2012), **BayesNetBP** (Yu, Moharil y Blair, 2019), **bnstruct** (Sambo y Franzini, 2019) and **bnlearn** (Scutari, 2010); the latter two can perform both tasks but the main goal that they seek is the structure and parameter learning.

**Analyzed Packages**

| Package | Version | Publication Year | Actual Version Year | Historical Downloads** | Semiannual Downloads*** |
| :---: | :---: | :---: | :---: | :---: | :---: |
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
** from October 2012 until March 2020
*** from October 2019 until March 2020
[Check the complete table here](https://github.com/LuisEduardoAngulo/BN-software-review-in-R/blob/master/Tables/1.%20Analyzed%20packages%2C%20complete%20table.csv)

Regarding the functionalities of each package:

| Functionality | catnet | sparsebn | pcalg | deal | bnclassify | bnstruct | bnlearn | gRain | BayesNetBP | 
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Structure learning | yes | yes | yes | yes | yes | yes | yes | no | no |
| Parameter learning | yes | yes | yes | yes | yes | yes | yes | no | no |
| BN classifier learning | no | no | no | no | yes | no | yes | no | no |
| Inference | no | no | no | no | no | yes | yes | yes | yes |
| Discrete data | yes | yes | yes | yes | yes | yes | yes | yes | yes |
| Continuous data | no | yes | yes | yes | no | yes | yes | no | yes |
| Mixed data | no | no | no | yes | no | no | yes | no | yes |
| Missing data | yes | no | no | no | yes | yes | yes | no | no |

# Bayesian Network Learning
---

The learning process can be split into two tasks, namely: structure learning and parameter learning. In the following subsection, you will find the built tables for each particular task.

### Stucture learning

* [Methods, algorithms, scores, independence tests and functions in R available in the analyzed packages for learning the network structure](https://github.com/LuisEduardoAngulo/BN-software-review-in-R/blob/master/Tables/2.%20Methods%2C%20algorithms%2C%20scores%2C%20independence%20tests%20and%20functions%20in%20R%20available%20in%20the%20analyzed%20packages%20for%20learning%20the%20network%20structure.csv)

* [Algorithms available in each analyzed packages](https://github.com/LuisEduardoAngulo/BN-software-review-in-R/blob/master/Tables/3.%20Algorithms%20available%20in%20each%20analyzed%20packages.csv)

* [Independence tests available per analyzed packages](https://github.com/LuisEduardoAngulo/BN-software-review-in-R/blob/master/Tables/7.%20Independence%20tests%20available%20per%20analyzed%20packages.csv)

* [Independence tests application according to the available type of data](https://github.com/LuisEduardoAngulo/BN-software-review-in-R/blob/master/Tables/5.%20Independence%20tests%20according%20to%20the%20available%20type%20of%20data.csv)

* [Scores available per analyzed packages](https://github.com/LuisEduardoAngulo/BN-software-review-in-R/blob/master/Tables/6.%20Scores%20available%20per%20analyzed%20packages.csv)

* [Score application according to the available type of data](https://github.com/LuisEduardoAngulo/BN-software-review-in-R/blob/master/Tables/4.%20Score%20according%20to%20the%20available%20type%20of%20data.csv)

### Parameter Learning

* [Methods, approaches and functions in R for parameter learning available in the analyzed packages](https://github.com/LuisEduardoAngulo/BN-software-review-in-R/blob/master/Tables/8.%20Method%2C%20approach%20and%20functions%20in%20R%20for%20parameter%20learning%20available%20in%20the%20analyzed%20packages.csv)

# Inference

* [Method, approach and functions in R for parameter learning available in the analyzed packages](https://github.com/LuisEduardoAngulo/BN-software-review-in-R/blob/master/Tables/8.%20Method%2C%20approach%20and%20functions%20in%20R%20for%20parameter%20learning%20available%20in%20the%20analyzed%20packages.csv)

# References
-----

* Aragam, B., Gu, J., y Zhou, Q. (2019). Learning Large-Scale Bayesian Networks with the sparsebn Package. Journal of Statistical Software, 91(11), 1–38.
* Balov, N., y Salzman, P. (2020). “How to use the catnet package”. Recuperado 30 de abril de 2020, de https://cran.r-project.org/web/packages/catnet/index.html.
* Boettcher, S., y Dethlefsen, C. (2003). deal: A Package for Learning Bayesian Networks. Journal of Statistical Software, 8(20), 1-40.
* Højsgaard, S. (2012). Graphical Independence Networks with the gRain Package for R. Journal of Statistical Software, 46(10), 1–26.
* Kalisch, M., Mächler, M., Colombo, D., Hauser, A., Maathuis, M., y Bühlmann, P. (2014). More Causal Inference with Graphical Models in R Package pcalg. Recuperado 10 de mayo de 2020, de https://cran.r-project.org/web/packages/pcalg/index.html.
* Mihaljevic, B., Bielza, C., y Larrañaga, P. (2018). bnclassify: Learning Bayesian Network Classifiers. The R Journal, 10(2), 455–468.
* Sambo, F., y Franzini, A. (2019). bnstruct: an R package for Bayesian Network structure learning with missing data. Recuperado 25 de abril de 2020, de https://cran.r-project.org/web/packages/bnstruct/index.html.
* Scutari, M. (2010). Learning Bayesian Networks with the bnlearn R Package. Journal of Statistical Software, 35(3), 1-22.
* Yu, H., Moharil, J., y Blair, R. (2019). BayesNetBP: An R package for probabilistic reasoning in Bayesian Networks. Recuperado 27 de mayo de 2020, de
https://www.researchgate.net/publication/336859662_BayesNetBP_An_R_package_for_probabilistic_reasoning_in_Bayesian_Networks.

