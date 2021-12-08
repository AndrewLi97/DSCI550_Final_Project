# DSCI550_Final_Project
#### vote_out.ipynb
This script finds out the the movies which have siginificant different voting point within two ratings systems. It also serves the function of joining the tables from two different csv datasets.

#### kmeans.ipynb
This script uses k-means algorithm to cluster the movies by revenue and voting average and also test different K number to find out the best fit K from mathematical perspective.

#### datacleaning_meta.ipynb
This script completed the initial data cleaning of the movies_metadata file. The data cleaning process removed entries that have duplicate and null values, and tranformed genres column from dictionaries to new variables for further analysis.

#### chelsey_data_cleaning
This script is used to extract key information from credit and movies_metadata file. From the credit table, new variables including number of crew by department, number of crew by gender, director names,gender of director number, of cast members, number of cast by gender are extracted, and defining reputable cast and director based on box office and popularity. 
From the movie_metadata file, new varibales including genres, number of production companies, number of production companies, language, release year, and seasonablity are generated.

#### Genere_classification
This script ran three different classification algorithms in order explore insights between genres and vote_averages. A new column named "Highrating" was created to differntiate high rating movies from low. The data were split into test set and training set. While the training set was used to create model, the test set was used to run the prediction and evaluation. 
