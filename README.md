## Boba in San Francisco, Californnia

## Motivation
Early this year I have left my boba job, but during my time there, my former co-workers and I would always think about the boba at other franchise; seeing if they'd be better or worse than where we working at. We all have been to various locations ourselves and wanted to decided what are the best boba locations. I was told California is the best place to look at due to the many varieties and rising number of boba franchise. What I wanted to get out of this was to see based on rating wise, which boba location is the best. 


## Data Source
The data I used was from Kaggle (https://www.kaggle.com/vnxiclaire/bobabayarea). This information was created about 4 years ago, thus meaning this data will not be accurate to today's time.

## Processing Steps
Due to the immense amount of boba locations in San Francisco, the original data has over 600 locations listed, even after clearing out dupilcate franchises, it dropped down to around 437 locations. I wanted to keep the information as simple as it could be. At one point, I cut it down to the first 100, and then to the first 50 locations; hoping the data would be easier to read. However in the end, I decided to cut it down to the first 25 locations in order to read the data a lot easier. 

Within the .csv files, I kept the original data, and the other file is the one with the deleted address, lat, and long columns since they were unnecessary data.   

## Visualization
When condensing down to the first 25 locations, all these locations are under 5 stars rating. The highest seems to be 4.5. At the same time, it's good to note that these 25 locations are starting at least around 3 stars. Clearly the graph tells me #20 and #22 stands out as the lowest from the first 25, rating at 3 stars each. 

![alt text](https://github.com/jessicaphan193/DATA115-Dataset_Project/blob/main/Rplot01.png)


## Analysis
While going through the data, one of the information that crossed my mind was the popularity of each city. Within the original data of the 603 locations, it wasn't surprsing to see San Jose would rank 1st as the most populated city.

![alt text](https://github.com/jessicaphan193/DATA115-Dataset_Project/blob/main/original_pt1.png)
![alt text](https://github.com/jessicaphan193/DATA115-Dataset_Project/blob/main/original_pt2.png)
![alt text](https://github.com/jessicaphan193/DATA115-Dataset_Project/blob/main/original_pt3.png)


However when removing the duplicates, and narrowing it down to 437 locations, it was a little surprsing to see San Francisco and San Jose to be evenly matched.

![alt text](https://github.com/jessicaphan193/DATA115-Dataset_Project/blob/main/middle.png)
![alt text](https://github.com/jessicaphan193/DATA115-Dataset_Project/blob/main/middle2.png)
![alt text](https://github.com/jessicaphan193/DATA115-Dataset_Project/blob/main/middle3.png)
