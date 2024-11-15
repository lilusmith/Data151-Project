# Data Analysis of Environmental Parameters of Soil


## Data151-Project

This project analyzed data from the previous research projects: Environmental Restoration Target Estimation Around Engquist Nature Preserve and Assessing Carbon Sequestration Potential of Cropland Conversion in Porter County, IN. These research projects collected data at Shirley Heinze Land Trust (SHLT) by students of the Geography Department at Valparaiso University, including Jack Colwell (member of this group), Korbin Opfer (current student), Doc Janowiak (recent alumnus), and Justin Self (recent alumnus). This research is also supported by Dr. Jon-Paul McCool of the Geography Department. Also of note is that this research is still ongoing this semester. These past projects collected soil samples from different environment types at properties owned by SHLT and the samples were subsequently analyzed for various soil parameters. The different environment types included prairie, forested wetland, forest, floodplain forested wetland, and agriculture. Environmental parameters that were specifically analyzed were bulk density, gravel mass, rock volume, soil volume, wet weight, dry weight, mineral sample, organic matter percent, soil organic carbon (SOC) percent, calcium carbonate percent, estimated carbon in horizon per sq. m. of soil, and estimated carbon in 10 cm depth per sq m. of soil.  
This project for DATA-151 explored healthy ranges for environmental variables for agriculture and then compared that to our existing dataset. It is important to develop a prediction for one or more variables within this dataset due to the cost and time to run all the tests. By modeling, we showed that one soil parameter can accurately predict another, or at least the magnitude and direction of another parameter. When these relationships are identified it can lead to accurate ways to take proxy measurements of soil parameters, rather than measure every single variable. 
The average soil organic carbon (SOC) content in Indiana soils varies depending on factors such as land management, soil type, and climate. In general, the SOC levels across Indiana agricultural soils are often between 0.67% and 2% in the topsoil layer (for our project, this means the top 10cm of a soil profile). Though some areas with organic-rich soils may exceed this range the estimated SOC range.
In order to develop our model, we ran different analyzation techniques, like a correlation matrix of the different parameters that were measured. Then these outcomes informed our predictive models, like a linear regression model and ANOVA. 
The project is important because of SOC’s necessity to agriculture and climate change, specifically global warming. In terms of agriculture, SOC helps farmers make informed decisions about their crops and soil management. The more knowledgeable farmers are about their soil health, the faster they can identify nutrient deficiencies or imbalances, which can be addressed before planting crops. In terms of climate change, soils hold a substantial amount of organic carbon, which can be released into the atmosphere as carbon dioxide if soils degrade, or prevented if managed sustainably, thus playing a significant role in the global carbon cycle. 


![image](https://github.com/user-attachments/assets/9c5d4fe0-fc6b-4efb-9dfa-a8b1409ed074)

# Best model results:
1.   Linear regression:
  *   MSE 0.201726  
  *   R squared 0.839502  
2.   Lasso [alpha 0.01]:
  *   MSE 0.30104
  *   R squared 0.76048
3.   Decision tree:
  *   MSE 0.74536
  *   R squared 0.40697







