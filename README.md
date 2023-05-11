# <img src=https://user-images.githubusercontent.com/122404051/235878740-0f447969-b786-41de-93ca-a4528a4db470.gif width="48" height="48" >  Zomato's Data Analysis
Developed a dashboard to generate data-driven insights by extracting and cleaning information from Zomato's webpage
Used Python libraries such as Selenium and BeautifulSoup to extract and parse unstructured data from the webpage
Imported the extracted data into Power Query Editor to clean and transform the data, resulting in two cleaned tables.
Provided actionable insights to a stakeholder planning to open a kitchen in Bangalore, including recommendations on cuisine, location, and pricing based on data analysis

<br>

##  <img src="https://user-images.githubusercontent.com/106439762/181935629-b3c47bd3-77fb-4431-a11c-ff8ba0942b63.gif" width="48" height="48"> *Folder Structure Guide*

| Files/Folder| Description |
| ------------- | ------------- |
| *.ipynb Folder* | This folder includes the Jupyter notebook files that were utilized to scrape the data from the web.  |
| *Dataset Folder* | Within this folder, there are two CSV tables that were acquired by scraping data from the web.  |
| *Presentation Folder* | This folder contains presentation in pdf as well as in ppt format.  |
| *Dashboard File* | This is Power BI-based dashboard that we developed to generate insights. |

<br>
<p align="center"><img src="https://user-images.githubusercontent.com/122404051/235879338-70ed6e1a-f192-4aee-9a0e-32ad1f001d87.gif"
 width="400" ></p>

## <img src=https://user-images.githubusercontent.com/106439762/178804195-d9db61fb-b2cf-4c8f-bfc3-214cfe0f534c.gif width="48" height="48" > Quick Summary

    1. Using Selenium And BeautifulSoup libraries of Python we Extracted data present on page and stored it in series and merging them to get DatFrame
    	a)MainPage Scrapper
	
  ![mainscrapper1](https://github.com/harshp1801/Recommender/assets/128036066/e37d3290-b15d-48be-8006-eb22f1c2ac1c.png)
    
  ![mainscrapper2](https://github.com/harshp1801/Recommender/assets/128036066/3fb8f688-3eda-40f9-867a-9201eb816636.png)
    
    	b)Restaurants info Scrapper
    
   ![subscrapper](https://github.com/harshp1801/Recommender/assets/128036066/ce5069e6-103a-4d49-9e11-bed1af538c9c.png)
 
    2. After obtaining the DataFrame we performed some data cleansing operation using Power Querry Editor and obtained two tables.
    
    3. Then, we imported the cleaned tables into MySQL and joined them.
    
    4. After joining the tables, we imported the dataset into Power BI in order to visualize the data.
    
    5. In Power Bi, we made some useful KPI's and some user friendly charts.
    
    6. Created a interactive and dynamic dashboard at the end using Power Bi and generated some useful insights.

    
##  <img src=https://user-images.githubusercontent.com/106439762/178803205-47a08ce7-2187-4f96-b301-a2b68690619a.gif width="48" height="48" > Prior Knowledge <br>
<br>
<p align="center"><a><img src="https://user-images.githubusercontent.com/122404051/235892949-3f3a82bb-6604-494e-bc9c-546fdb4bbdc0.jpg" width="850" height="40"></a></p>


<br>
    
 
##  <img src="https://user-images.githubusercontent.com/122404051/235767211-297f9f4f-d41a-46ec-838f-13ea23817702.gif"  width="48" height="48"> Analysis 
	
    o As per the Area-wise distribution of  restaurants, BTM has the highest and Sadashiv Nagar has the least no of restaurants.

    o 1 Sobha has the highest avg price around ₹ 400 while City market has the lowest avg price around ₹ 30 .

    o "Pure Veg Meals By LunchBox" in Shanti Nagar is the most expensive restaurant with avg price around ₹ 800 - 900 while "The Taj Hotel" in City market has the lowest avg price around ₹ 30 .

    o Basavanagudi has the most reviewed restaurant with over 5 lakh+ reviews in total.
    
    o North Indian cuisine the most preferred cuisine by the consumers and hence are provided the most


## <img src="https://img.icons8.com/dusk/48/000000/ios-screenshot.png"/> Dashboard Screenshot

![dashboard power bi](https://user-images.githubusercontent.com/122404051/235893746-ea44df0d-183f-4c56-b379-29bef3970ae7.jpg)


<br>

## <img src="https://user-images.githubusercontent.com/108053296/185756908-fbb62168-d923-48f2-992f-b8e2fde848fe.gif" width="48" height="48" > Conclusion


As per our analysis, if the person wants to open a remote kitchen in Bangalore he/she should prefer opening it in Shanti Nagar or Basavanagudi, since the place is having less no of restaurant which reduces the competition and it has some of the expensive restaurants in the Banglore, hence the person can deliver food at lower price which reduces the competition even further.

The second suggestion would be sell North Indian, South Indian cuisine as they are demanded the most by the customers and they can keep the price ranging from 300 - 400 Rs for Non vegetarian category and 200 - 300 Rs for vegetarian category.
