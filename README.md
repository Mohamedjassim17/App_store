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

                                                      Data set information
1. Column Name: id,
   Description: App ID

2. Column Name: track_name,
   Description: App Name

3. Column Name: size_bytes,
   Description: App Size in bytes

4. Column Name: currency,
   Description: Currency Type

5. Column Name: price,
   Description: Price amount

6. Column Name: ratingcounttot,
   Description: User Rating counts (for all versions)

7. Column Name: ratingcountver,
   Description: User Rating counts (for current version)

8. Column Name: user_rating,
   Description: Average User Rating value (for all versions)

9. Column Name: userratingver,
   Description: Average User Rating value (for current version)

10. Column Name: ver,
    Description: Latest version code

11. Column Name: cont_rating,
    Description: Content Rating

12. Column Name: prime_genre,
    Description: Primary Genre

13. Column Name: sup_devices.num,
    Description: Number of supporting devices

14. Column Name: ipadSc_urls.num,
    Description: Number of screenshots showed for display

15. Column Name: lang.num,
    Description: Number of supported languages

16. Column Name: vpp_lic,
    Description: Vpp Device Based Licensing Enabled


                                                        Visualtion
• The top app categories are used for data visualization with Seaborn.

 ![image](https://github.com/Mohamedjassim17/App_store/assets/134086605/913bed01-b0a7-4c78-bbae-3572ecb2da67)

• The low app categories are used for data visualization with Seaborn.

![image](https://github.com/Mohamedjassim17/App_store/assets/134086605/675a2a5c-4cb6-48a4-8c48-7c5fbc142945)








                                          
                                              
