
# Movie Recommendation 
The goal of this project is to implement various recommendation techniques (such using the surprise package) to examine how each technique works. 

# Overview
Presentation: https://github.com/mcumiskey/Aviation-Risk-Analysis/blob/main/Presentations/Phase%201_%20Aviation%20Project.pdf


## Business Understanding
There are a lot of movies to watch! 

The goal is to be able to use a collaborative recommendation to provide a user movies suggestions enjoyed by other user with similar tastes. Additionally, we will use a content-based recommendation system be able to suggest movies that are similar to movies they have already watched. 

## Data Understanding and Analysis

The data is from [MovieLens](https://grouplens.org/datasets/movielens/latest/). It contains 100,000 ratings and 3,600 tag applications applied to 9,000 movies by 600 users. Last updated 9/2018
![most movies are from the 1980s - 2010s](img/image-4.png)

![Forrest Gump is a frequently rated movie](img/image-2.png)

![most ratings are in the 3-4 range (on a scale of 0.5 to 5)](img/image-1.png)

![highest and lowest rated movies with a significant number of reviews](img/image-3.png)

## Conclusion
I am able to provide recommendations with a rmse of 0.8. (meaning, our predicted score for a movie-user combo may be off by around 0.8 points!)

- provided specific recommendations for a random user.

## Next Steps 
**Combine** the various approaches to create a hybrid model 

**Use an NLP model to group movies with similar tags** 

**Add influencer recommendations** to highlight specific movies 


## Project Structure 
```
├── Presentations
│   ├── notebook.pdf
│   ├── github.pdf
│   └── Phase_1_Aviation Project.pdf
├── data
│   ├── AviationData.csv
│   └── USState_Codes.csv
├── images
│   ├── airplane-isolated-on-transparent-background-3d-rendering-aircraft-png-2455088391.png
│   ├── horizontal_div_left.png
│   └── horizontal_div_right.png
├── .DS_Store
├── .gitignore
├── README.md
└── aviation analysis conclusion.ipynb
```