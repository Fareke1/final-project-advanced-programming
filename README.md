# final-project-advanced-programming
 
REPORT FINAL EXAM ADVANCED PROGRAMMING

FROM: Yeshim Salimkhan and Zhubatkan Farukh (IT-2203)

TO: Advanced Programming’s teacher

TOPIC: Historical earthquake data of Kazakhstan and neighboring countries (1991-2024)

1. Introduction

a) Problem:

Earthquakes pose significant threats to human life and infrastructure. Understanding their occurrence patterns and characteristics is crucial for disaster preparedness and mitigation efforts. Traditional methods of earthquake analysis often involve manual inspection of seismic data, which can be time-consuming and may lack scalability.

b) Literature Review:

   - USGS Earthquake Hazards Program: (https://earthquake.usgs.gov/)
     
   - Basemap Documentation: (https://matplotlib.org/basemap/)
     
   - Cartopy Documentation: (https://scitools.org.uk/cartopy/docs/latest/)
    
   - TensorFlow Documentation: (https://www.tensorflow.org/)
  
   - NumPy Documentation: (https://numpy.org/)

   - Scikit-learn Documentation: (https://scikit-learn.org/stable/)

These resources provide valuable information on earthquake monitoring, visualization techniques, and deep learning frameworks.

c) Current Work:

In this project, we utilize Python libraries such as Pandas, Matplotlib, Basemap, Cartopy, and Scikit-learn to analyze earthquake data in Kazakhstan from 1991 to 2024. We start by visualizing the spatial distribution of earthquakes using Basemap and Cartopy. Next, we explore the distribution of earthquake magnitudes and depths. Finally, we employ a Random Forest classifier from Scikit-learn to predict earthquake occurrences based on geographical and seismic features.
   
3. Data and Methods
   
- Data Information:
  
  The earthquake data is sourced from the USGS Earthquake Catalog, covering the region of Kazakhstan from 1991 to 2024. It includes parameters such as time, latitude, longitude, depth, and magnitude of earthquakes.
  
- Visualization:
  
  We use Matplotlib and Cartopy to visualize earthquake events spatially on a map of Kazakhstan, as well as to plot histograms showing the distribution of earthquake magnitudes and depths.
  
- Machine Learning/Deep Learning Models:
  
We utilize a Random Forest classifier, a popular ensemble learning method, to predict earthquake occurrences. Random Forest builds multiple decision trees during training and outputs the class that is the mode of the classes (classification) or mean prediction (regression) of the individual trees.
  
3. Results
   
- Spatial Distribution:
  
  The scatter plot on the map of Kazakhstan illustrates the spatial distribution of earthquakes, with larger magnitude events represented by larger and darker points.

![image](https://github.com/Fareke1/final-project-advanced-programming/assets/153728604/87c778aa-1ff3-45b5-a674-6026af85e6eb)


- Magnitude and Depth Distribution:
  
  Histograms display the frequency distribution of earthquake magnitudes and depths, providing insights into their characteristics.

![image](https://github.com/Fareke1/final-project-advanced-programming/assets/153728604/735c656e-f4d3-47b2-b67a-c8158e140ca5)

![image](https://github.com/Fareke1/final-project-advanced-programming/assets/153728604/f44f0486-82c2-43ba-a4a9-f19c025d5ae7)

 
- Temporal Patterns:
  
  The temporal plot shows the number of earthquakes occurring each year, indicating any notable trends or variations over time.

![image](https://github.com/Fareke1/final-project-advanced-programming/assets/153728604/11922122-74c0-4b69-a325-e55e103b644d)

- Model Performance:
The Random Forest classifier achieves an accuracy of accuracy_score on the test set. Classification report provides detailed metrics such as precision, recall, and F1-score for earthquake occurrence prediction.


![image](https://github.com/Fareke1/final-project-advanced-programming/assets/153728604/9263508c-901c-4718-9fc9-00dd9eaebc8a)

- Feature Importance:
Feature importance plot reveals the significance of geographical and seismic features in predicting earthquake occurrences.

![image](https://github.com/Fareke1/final-project-advanced-programming/assets/153728604/783f13ca-97e8-465d-8b12-87026a9073e0)
 
d) Discussion

- Critical Review:
  
The analysis provides valuable insights into earthquake patterns and characteristics in Kazakhstan. However, the predictive performance of the Random Forest classifier may vary depending on the quality and quantity of the data.

- Next Steps:
  
Future work could involve refining the machine learning model, exploring other algorithms, incorporating additional features, and validating the model's predictions with real-world earthquake data.

![image](https://github.com/Fareke1/final-project-advanced-programming/assets/153728604/d8fc1feb-5713-4d68-a9d1-399d0b168ba1)


 
From here we selected the start and end time and chose the range

Links:

https://earthquake.usgs.gov/

https://matplotlib.org/basemap/

https://scitools.org.uk/cartopy/docs/latest/

https://www.tensorflow.org/

https://numpy.org/

https://scikit-learn.org/stable/
