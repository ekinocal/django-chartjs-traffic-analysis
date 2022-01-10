# django-chartjs-traffic-analysis
Traffic dataset analysis with python and used django and chartjs


1.6 million UK traffic accidents

The UK government amassed traffic data from 2000 and 2016, recording over 1.6 million accidents in the process and making this one of the most comprehensive traffic data sets out there. It's a huge picture of a country undergoing change.
Firstly, I showed the accidents that occurred at separate whole year intervals in a bar graph and a pie graph. The reason for using the pie chart was to be able to see the percentiles.

![image](https://user-images.githubusercontent.com/61598281/148847222-995ca062-ce9d-4f00-ad7b-636373c00f2e.png) ![image](https://user-images.githubusercontent.com/61598281/148847243-584a081c-57c0-4495-b824-8c3e67352ca8.png)

Then combined all the relevant datasets into one dataset. In this way, I would be able to do a more comprehensive research from 2005 to 2014. Using this dataset I created a combined histogram chart with all the useful columns.  Since I thought the road types would be a useful graph, I wanted to visualize it as well, and I created a bar graph using the combined dataset.
![image](https://user-images.githubusercontent.com/61598281/148847301-48aed928-3b78-4f16-8100-88ae394eac34.png) ![image](https://user-images.githubusercontent.com/61598281/148847314-1a3c01c4-bc3f-4531-9b0d-3c5a8f81d7e7.png)

I created pivots with the help of the pandas library to classify the accident severity by months. I gave them 1 2 3 values and they all represented the severity. Then I imported the data I found into plo and bar graphs to visualize. This was one of the most difficult parts of the whole work.
![image](https://user-images.githubusercontent.com/61598281/148847362-8577614b-e588-4ea0-bfed-de9b6652dae1.png) ![image](https://user-images.githubusercontent.com/61598281/148847389-bf78ae29-a008-45b0-9cad-7faf5e91d2ba.png)

Finally, I wanted to visualize the data that caused the crash. I thought this would be very helpful. I visualized all the reasons.![image]

![image](https://user-images.githubusercontent.com/61598281/148847430-1bde61d2-5c06-4855-b433-a5b6e3971750.png) ![image](https://user-images.githubusercontent.com/61598281/148847451-7c81f25a-6a4a-40a3-b8e3-82fd04c223d1.png)

Django

Django was a new experience for me. I've never been interested in web programming before and I've never used the django framework. This was the part that took the most time and had difficulty. My goal here was to visualize the vehicle and casualities columns after selecting and loading the csv files as we want, because I saw these two as the most appropriate columns to visualize. I determined the indexes according to the accident index. I made the necessary edits in my index.html document. I used char js and papa parse during this visualization and edits.!

![image](https://user-images.githubusercontent.com/61598281/148847592-0d8b529c-2489-47b7-ab2f-cf63b765d8ec.png)


Dataset Link: https://www.kaggle.com/daveianhickey/2000-16-traffic-flow-england-scotland-wales
