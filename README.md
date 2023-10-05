# Data-Collection
## Scope
Via automated browsing with Splinter and HTML parsing with Beautiful Soup, we were given 2 websites to scrap. 
  
On the "Mars news site" (https://static.bc-edx.com/data/web/mars_news/index.html), the task was to find all the article titles and preview information and save it in a dictionary on Python.  
  
For the second task, we were given the website the "Mars Temperature Data Site" (https://static.bc-edx.com/data/web/mars_facts/temperature.html) and by using Beautiful Soup, we had to extract the table, run some analysis on the data to answer required questions and store the table extracted on a CSV file.   
## Results
### Mars news site
A screenshot of the final Python dictionary with the Mars new site information.  
![image](https://github.com/JulianRavelo/Data-Collection/assets/132871396/58c79ffb-a8d9-40ff-b528-7fcae17a08f6)  
### Mars Temperature Data Site  
The given questions to answer were:
- How many months exist on Mars?
  The table below shows the number of days per month on Mars  
![image](https://github.com/JulianRavelo/Data-Collection/assets/132871396/a72f173d-b805-4ac8-8db2-ce5d703963ee)  
- How many Martian days' worth of data are there?
  There are 1867 days' worth of data on that table
![image](https://github.com/JulianRavelo/Data-Collection/assets/132871396/34e57762-6034-4282-805f-cf32e752027c)
- Which month, on average, has the lowest temperature? The highest?
  On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest as shown below  
![image](https://github.com/JulianRavelo/Data-Collection/assets/132871396/036341f1-5ac9-4ec1-9cef-2ff84901b971)
- Which month, on average, has the lowest atmospheric pressure? The highest?
  Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth as shown below
![image](https://github.com/JulianRavelo/Data-Collection/assets/132871396/60d1c8e1-19c2-4825-9e73-9e3959c869d5)
- How many terrestrial days exist in a Martian year? A visual estimate of 25% was made.
  The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 Earth days  
![image](https://github.com/JulianRavelo/Data-Collection/assets/132871396/6a9bbf2b-b45a-472a-8c0c-08102d677fc8)  
## Resources  
- https://saturncloud.io/blog/convert-pandas-column-to-datetime-a-guide/#:~:text=To%20convert%20a%20pandas%20column,new%20column%20with%20datetime%20values.  
- https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.astype.html  
- https://stackoverflow.com/questions/45759966/counting-unique-values-in-a-column-in-pandas-dataframe-like-in-qlik  
