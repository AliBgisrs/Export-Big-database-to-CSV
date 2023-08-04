# Export-Big-database-to-CSV
This tool export big database into a csv file
Project Title
[Export Big database into csv file format]
Description
[if you are using machine learning and deep learning models and need to export your feature layer with a big database (million rows od data) into csv file for feeding your model, using this script is highly recommended]
 
Table of Contents
•	Installation
•	Usage
•	Contributing
•	License
Installation
[Download the script]
[Go to the insert tab of your ArcGIS PRO project]
 
[Select add folder and browse to the folder that you have saved your script and add that folder]
[Go to the Catalog and find your folder in the Folders section and then find the tool with the name of FeaturelayerToCSV, then open it to find the script]
 
 
[Double click and open the script]
 
[Call the input feature layer (your feature layer that you want to export its attribute table) . Note: You should have a feature layer not shape file. 

 
Before running the tool you should create a folder in your C drive directory to save the results on there. 
 
Usage
Assume that you are going to run a deep learning model in python using your spatial data. You have a feature layer with 2o million rows. If you want to export that dataset just by copying it to Excel or using a table to Excel tool in ArcGIS, your data just save for the first 1,048,576 rows (the maximum number of rows supported in a worksheet is 1,048,576), so you need to export that attribute table to other format like csv that supports big datasets. For example, in my example, I have a dataset with 20658793 rows of data. In ArcGIS, there is no such specific tool for doing this task. So, this tool can help users to call the feature layer and save the attribute table in CSV file in your directory (C drive). 
 
After running the tool two csv file will be created in you csv folder at your C drive. 
 
If your dataset is so big you can use temp.csv file otherwise you can use YourCSV.csv file. Then you can open those files in you python notebook.
 
Contributing
[Please run the script, use it and help me to improve the performance of that script using your valuable suggestions.]
License
About the Author
[Developed by Aliasghar Bazrafkan.]
Acknowledgments
[I would like to express my sincere appreciation to my supervisor, Dr. Paulo Flores, from North Dakota State University (NDSU), for providing invaluable support and guidance throughout the development of this script. His expertise and encouragement have been instrumental in making this project possible].
Contact
[Aliasghar.bazrafkan@ndus.edu]
Additional Notes
[https://sites.google.com/ndsu.edu/floreslab/home?authuser=0]
