# Excel_Project
Creating a simple excel project to demonstrate skills in creating a dashboard.


PROJECT NAME – Bike Sales Dashboard

OBJECTIVES

1. Create visualization of the bike sales
2. Create some filters to interact with the data
   
QUERIES

When considering the customer audience, there are many factors to look into. The factors addressed in this project are:
1. Average income of a person who bought a bike or who didn’t buy a bike.
2. Commuting distance of a person from home to workplace.
3. Age brackets.

INSTRUCTIONS

Create the following three worksheets
1. Working sheet – this is a copy of the dataset which we will work on and keep the original file of the dataset for reference.
   Clean the data
   1. Check for duplicates - (Command : data tab -> data tools -> remove duplicates)
   2. Remove short forms – short forms create confusion and the dataset contains two columns with short forms(marital status and gender). Find and replace with the full word. - (Command : ctrl h (search by all columns))
   3. Correct the currency – income column has dollar signs within the data which can create a mess with calculations
   4. Create age brackets
   5. Correct commute distance range – when performing visualization you get the following error as the naming of the columns are incorrect hence we correct the naming in a way that the range in the visualization is optimum. 
 ![image](https://github.com/hibahsalam/Excel_Project/assets/63388880/2f5cbe6d-4ece-44e6-afbf-1fd909aafa7e)

2. Pivot Table - to generate charts – (Commands : insert tab -> charts -> recommended charts)
   1. Average income of a person that bought a bike verses who didn’t buy a bike
      Values – income
      Rows – gender
      Columns - purchased bike
      
 ![image](https://github.com/hibahsalam/Excel_Project/assets/63388880/08440dd5-b6a6-40d1-870c-984a9220e40e)

   2. Commuting distance of a person from home to their workplace
      Values – purchased bike
      Rows – commute distance
      Columns - purchased bike
      
 ![image](https://github.com/hibahsalam/Excel_Project/assets/63388880/77501316-aae0-4b8b-97b2-5906d3fdeafa)


	3. Age brackets are a factor to consider in the sales of bikes
      Values – purchased bike 
      Rows – age brackets
      Columns - purchased bike
      
 ![image](https://github.com/hibahsalam/Excel_Project/assets/63388880/95930fea-9f68-4db7-921c-413a0e6d3702)


•	Dashboard 
	Presentation - remove gridlines to make it look nice.
	Make a title header – “Bike Sales Dashboard” and ‘ merge and center’.
	Arrange charts and align according to your requirements.
	There are other element people would like to filter by, for example, single vs married. Are single people buying more bikes compared to married people?
(Command – click on any chart -> pivotChartAnalyze tab -> filter -> insert slicer)
	To apply slicer to all visualizations –
 (Command : click on the slicer -> slicer tab -> report connections and select your choice of pivot tables)

 ![image](https://github.com/hibahsalam/Excel_Project/assets/63388880/6748a67e-204f-4ca3-a466-17f6668b2d8c)





