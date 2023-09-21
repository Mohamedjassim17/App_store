# App_store
                                                       OverView
                                                

![1_JA6oELHXXNUjCPruio6glw](https://github.com/Mohamedjassim17/App_store/assets/134086605/6511ff8f-ccd9-48bb-9666-36cd3906f90b)

                                                      Introduction

 •Nowadays, the percentage of mobile usage compared to desktop is continually increasing. Android holds approximately 53.2% of the smartphone market, while iOS commands a 43% share.

 •When it comes to app preferences, we aim to determine whether users tend to download paid or free apps more frequently. 

 •Additionally, we analyze the ratings associated with these apps and provide visualizations to illustrate the findings.

 •For this analysis, we employ the K-Means machine learning algorithm.

                                                       Intel DevCloud
  ![image](https://github.com/Mohamedjassim17/App_store/assets/134086605/0912187e-3689-4430-a99d-df879078809e)


DevCloud for oneAPI provides a library of highly optimized algorithms for data preprocessing and analysis, specifically designed to accelerate machine learning workloads on a diverse set of Intel architectures. DevCloud is an all-in-one online destination to test the performance of your AI models on Intel processors. It's a dedicated space that allows developers and engineers to innovate in a production-ready space. What's great about this platform is that it gives you access to dedicated Intel technology – without having to invest in hardware upfront.

Key Features

The latest Intel hardware, including Intel Core processors, Intel Xeon Scalable processors, Intel IoT developer kits and Intel FPGAs
Intel-optimized frameworks – the latest version of OpenVINO
This project is executed in Jupyter Notebook provided by Intel DevCloud, in One API platform

                                                       Importing Libraries:
                                                    
 • pandas and numpy are used for data manipulation and numerical operations.
 
 • matplotlib.pyplot is used for creating data visualizations.

 • seaborn is a data visualization library that works well with pandas.
 
 • warnings is used to suppress warning messages.
 
 • RobustScaler is an instance of scikit-learn's RobustScaler, used for robust data scaling.
 
 • KMeans is a clustering algorithm from scikit-learn used for K-Means clustering.
 
 • silhouette_score is a metric used to evaluate the quality of clusters.

 • PPS (Predictive Power Score)

                                                      Data set information

| Column Name       | Description                                     |
|-------------------|-------------------------------------------------|
| id                | App ID                                          |
| track_name        | App Name                                        |
| size_bytes        | App Size in bytes                               |
| currency          | Currency Type                                   |
| price             | Price amount                                    |
| ratingcounttot    | User Rating counts (for all versions)          |
| ratingcountver    | User Rating counts (for current version)       |
| user_rating       | Average User Rating value (for all versions)   |
| userratingver     | Average User Rating value (for current version)|
| ver               | Latest version code                             |
| cont_rating       | Content Rating                                  |
| prime_genre       | Primary Genre                                   |
| sup_devices.num   | Number of supporting devices                    |
| ipadSc_urls.num   | Number of screenshots showed for display       |
| lang.num          | Number of supported languages                   |
| vpp_lic           | Vpp Device Based Licensing Enabled              |


                                                        Visualtion
    
• The top app categories are used for data visualization with Seaborn.

 ![image](https://github.com/Mohamedjassim17/App_store/assets/134086605/913bed01-b0a7-4c78-bbae-3572ecb2da67)

• The low app categories are used for data visualization with Seaborn.

![image](https://github.com/Mohamedjassim17/App_store/assets/134086605/675a2a5c-4cb6-48a4-8c48-7c5fbc142945)


The count of free app users and paid app

![image](https://github.com/Mohamedjassim17/App_store/assets/134086605/1b88f535-aec2-4a5e-909d-4918b96edbd2)

• Top Price in important Category (Business , Navigation , Education , Productivity )                                               

• in another side price for all of apps less than 50 USD

• Education Apps has a higher price

• Shopping Apps has a lower price








                                          
                                              
