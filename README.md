# IMDb
Python project for analysing IMDb data

## Prerequisites
- ```bokeh```
- ```numpy```
- ```pandas```

## How to run
- Make sure you have the prerequisites installed
- Clone this project
- In your shell, go to the cloned project
- Type ```jupyter notebook IMDb.ipynb```

## Results

### 1. Create histograms of rating, length and length of title.
#### Histogram of rating
The image below shows how the ratings are distributed.
There is an error in the graph, which shows, that there are a lot of occurences of the 5.4 rating, which is in fact not true.
Most movies are rated a bit above the middle - with the rating of 6. 
![alt tag](https://github.com/ziemerz/IMDb/blob/master/ratings.png)

#### Histogram of length in minutes
This histogram shows the length distribution of the movies.
From the data we can see that the vast majority og movies are of 90 minutes of length.
![alt tag](https://github.com/ziemerz/IMDb/blob/master/length.png)

#### Histogram of length of movie titles
As you can see from the histogram, the length of titles are most usual 14 characters long
![alt tag](https://github.com/ziemerz/IMDb/blob/master/lot.png)

### 2. Create a graph showing both year and amount of movies made.
The graph clearly shows that there was a boom in the last months leading up to 2005. The reason the graph is falling in 2005, is that this data was from early 2005.
![alt tag](IMDb/amount.png)

### 3. Make a scatter-plot with year and length of movies.
This scatterplot shows the distribution of all of the movies. 
The second one shows the same thing, but zoomed in to leave out data which are way different than the majority. 
The second plit also shows animated movies as the green dots. 
![alt tag](https://github.com/ziemerz/IMDb/blob/master/scatter.png)
![alt tag](https://github.com/ziemerz/IMDb/blob/master/animated.png)

