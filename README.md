## Georgetown University PPOL-6803, Intro to Data Science Final Project: China Aging Population Analysis: A Machine Learning Method of Health Status Prediction

He, Yuyan (@yuyanhe0202, email: yh915@georgetown.edu); 
Huang, Grace (@gracehuang-xjh, email: yh872@georgetown.edu); 
Yang, Qingya (@qy112-yqy, email: qy112@georgetown.edu); 
Yu, Qingfeng (@MessaihYu, email: qy111@georgetown.edu)


#### Citation

Clark, C. R., Ommerborn, M. J., Moran, K., Brooks, K., Haas, J., Bates, D. W., & Wright, A. (2021). Predicting self-rated health across the life course: Health equity insights from machine learning models. Journal of General Internal Medicine, 36(5), 1181–1188. https://doi.org/10.1007/s11606-020-06438-1

Choi, J. H. (Steph), & Jung, D. H. (2025). The role of psychological factors in predicting self-rated health: Implications from machine learning models. Psychology, Health & Medicine, 30(6), 1861–1876. https://doi.org/10.1080/13548506.2025.2450546

Fan, Y., & He, D. (2022). Self-rated health, socioeconomic status and all-cause mortality in Chinese middle-aged and elderly adults. Scientific Reports, 12, Article 9309. https://www.nature.com/articles/s41598-022-13502-9

National Bureau of Statistics of China. (2018). National data: EasyQuery (E0103) [Data set]. Retrieved December 20, 2025, from https://data.stats.gov.cn/easyquery.htm?cn=E0103

Qi, Y. (2014). Reliability and validity of self-rated general health in China. Chinese Journal of Sociology, 34(4), 196–212. https://www.ccpr.ucla.edu/wp-content/uploads/2022/06/Qi-Yaqiang.pdf

Yu, G. (n.d.). chinamap: China map data (Version 0.2.0) [R package]. GitHub. Retrieved December 20, 2025, from https://github.com/GuangchuangYu/chinamap

Zhang, X., Wu, M., Chen, C., & Guo, Y. (2021). Self-rated health status and its influencing factors among the elderly in China: Based on the 2018 China Health and Retirement Longitudinal Study. Medicine, 100(48), e27772. https://doi.org/10.1097/MD.0000000000027772

China Health and Retirement Longitudinal Study. (n.d.). CHARLS (China Health and Retirement Longitudinal Study). Peking University. Retrieved December 20, 2025, from https://charls.pku.edu.cn/en/


#### Repository Contents

This repository contains the following files/folders:

-   `data`
-   `final_project.qmd`
-   `final_project.html`
-   `graph`
-   `presentation`

Descriptions of folder contents can be found below.

#### data

This folder contains the data used for this project. This folder was not pushed due to file size. Full data could be accessed through the Google Drive link below:
https://drive.google.com/drive/folders/1F3IVGoFFbbMIjjTwQAkFL6sRhgp-wFaf?usp=drive_link

CHARLS Dataset was retrieved from: https://charls.pku.edu.cn/en/

-  `Final_2018Merged.RData`: merged CHARLS 2018 dataset, generated from `merge code2.R`
-  `Raw Data`: used for merging the merged CHARLS 2018 dataset
-  `Exertal Data`: GDP and healthcare resources data by province
-  `Official Codebook, Guidbook, and Userbook`: official materials for CHARLS 2018 dataset
-  `merge code1.R`, `merge code2.R`: R scripts for merging data from CHARLS and NBSC
-  `rule of merging.xlsx`: merging rules
-  `CHARLS2018_merged.dta`: generated from `merge code1.R`


#### final report

- `final_project.qmd`: The final project contains all scripts and analytical narratives related to the project
- `final_project.html`: The rendered version of the above report.

#### graph

This folder contains all `.png` figures produced in the analysis:

-  `importance_rf.png`: Plot used for checking variable importance of Random Forest regression model.
-  `importance_rf_age.png`: Plot used for checking variable importance of final Random Forest regression model by age group and variable category.
-  `china_gdp.png`: Plot of China GDP using GIS package
-  `china_health.png`: Plot of China GDP using using main data and GIS package
-  `china_hospital.png`: Plot of China GDP using healthcare resources data and GIS package
-  `china_income.png`: Plot of China GDP using main data and GIS package
-  `china_medical_professinals.png`: Plot of China GDP using main data and GIS package


#### presentation

This folder contains the PDF of the final project presentation.

