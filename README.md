# Data Analysis of Environmental Parameters of Soil


## Data151-Project Executive Summary

Soil organic carbon, or SOC, is an important metric to understand in an era of changing climate and ever advancing agricultural technologies. SOC is the organic matter in the soil that is composed of carbon and can be released into the environment from microbial respiration. 
Data Analysis of Soil Parameters at a Local Land Preserve used a data analysis approach to analyze data previously collected in a study titled Environmental Restoration Target Estimation Around Engquist Nature Preserve by Jack Colwell and other students at Valparaiso University. This project's objective is to use our various soil parameters as predictors for SOC in the previously collected soil samples. We also compared our data to an optimal range for SOC levels. The SOC content in soil varies, influencing the ability to manage healthy agriculture and the global carbon cycle. Understanding these SOC levels helps farmers make more informed decisions on how to maintain healthy soil levels and mitigate climate change. 

The data was cleaned and errors were removed using Python in a Google Colab environment. Then a correlation matrix was created to narrow down the highest correlated variables to use in our prediction for SOC content. From this matrix, it was found that two variables from this dataset are the best predictors to use: Carbonate-Free Mineral Sample (g) and Mineral Sample (g). By using these two variables, several regression models were run to output the RMSE (Root Mean Square Error) and R2 value of each regression model, as these results influence the decision on which model is best to apply. 
Key findings indicate that the random forest regressor, which tends to resist overfitting, is the best model for this situation and data. 

That predictive model outputs are as follows:

≈ 0.760 RMSE

≈ 0.914 R²

This means that approximately 91.4% of the variance in the data can be explained by our model. That is to say, using these two variables, the SOC content can be reliably predicted, without a direct measure of SOC content itself. 
These findings demonstrate that accurate SOC predictions can be achieved without measuring all variables, significantly reducing costs and time. By optimizing soil testing practices, farmers can improve crop management and enhance resilience to climate change. Moreover, this research aligns with broader goals in climate-smart agriculture by supporting efforts to increase soil carbon stocks and reduce greenhouse gas emissions.
