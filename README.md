# Export-Big-database-to-CSV

This tool exports big database into a csv file

Project Title

[Export Big database into CSV file format]

Description
[if you are using machine learning and deep learning models and need to export your feature layer with a big database (million rows of data) into csv file for feeding your model, using this script is highly recommended]

![image](https://github.com/AliBgisrs/Export-Big-database-to-CSV/assets/109620013/c304df99-79ae-45fc-afb6-80245e654b23)


 
Table of Contents

•	Installation

•	Usage

•	Contributing

•	License


Installation

[Download the script]
[Go to the insert tab of your ArcGIS PRO project]

![image](https://github.com/AliBgisrs/Export-Big-database-to-CSV/assets/109620013/1fcc7f40-baae-491c-b99e-9419781f2807)

 
[Select add folder and browse to the folder that you have saved your script and add that folder]
[Go to the Catalog and find your folder in the Folders section and then find the tool with the name of FeaturelayerToCSV, then open it to find the script]
 

![image](https://github.com/AliBgisrs/Export-Big-database-to-CSV/assets/109620013/8d014d04-c7f7-4bbd-83ff-05bb265bc30c)


 ![image](https://github.com/AliBgisrs/Export-Big-database-to-CSV/assets/109620013/00712338-1d73-4341-9f41-3ef582225a36)
 

[Double click and open the script]

![image](https://github.com/AliBgisrs/Export-Big-database-to-CSV/assets/109620013/4885c6bc-9591-43f9-880a-a2a18a8edf79)

 
[Call the input feature layer (your feature layer that you want to export its attribute table) . Note: You should have a feature layer not shape file. 

![image](https://github.com/AliBgisrs/Export-Big-database-to-CSV/assets/109620013/f88255aa-c8aa-46bd-ba18-9fe676e8b7d5)


 
 
Usage

Assume that you are going to run a deep learning model in python using your spatial data. You have a feature layer with 2o million rows. If you want to export that dataset just by copying it to Excel or using a table to Excel tool in ArcGIS, your data just save for the first 1,048,576 rows (the maximum number of rows supported in a worksheet is 1,048,576), so you need to export that attribute table to other format like csv that supports big datasets. For example, in my example, I have a dataset with 20658793 rows of data. In ArcGIS, there is no such specific tool for doing this task. So, this tool can help users to call the feature layer and save the attribute table into a CSV file in your directory. 

![image](https://github.com/AliBgisrs/Export-Big-database-to-CSV/assets/109620013/2f858df1-ddf4-48fb-80e0-e9af76a5cbc6)

 
After running the tool a CSV file format will be created in your output directory. 

![image](https://github.com/AliBgisrs/Export-Big-database-to-CSV/assets/109620013/2618ffae-5852-4a2c-824b-cd1ce494b866)

 
Then you can open that file in your Python notebook.

![image](https://github.com/AliBgisrs/Export-Big-database-to-CSV/assets/109620013/aaf8c9fd-4594-4fd6-8f0d-3cabacb6f534)

 
Contributing

[Please run the script, use it, and help me to improve the performance of that script using your valuable suggestions.]

License


About the Author

[Developed by Aliasghar Bazrafkan.]


Acknowledgments

[I would like to express my sincere appreciation to my supervisor, Dr. Paulo Flores, from North Dakota State University (NDSU), for providing invaluable support and guidance throughout the development of this script. His expertise and encouragement have been instrumental in making this project possible].

Contact

[Aliasghar.bazrafkan@ndus.edu]

Additional Notes

[https://sites.google.com/ndsu.edu/floreslab/home?authuser=0]
