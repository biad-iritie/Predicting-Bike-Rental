# Predicting Bike Rentals

Many U.S. cities have communal bike sharing stations where you can rent bicycles by the hour or day. Washington, D.C. is one of these cities. The District collects detailed data on the number of bicycles people rent by the hour and day.

You can have the data from the [University of California, Irvine's website](http://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset)
Description of the data : 
| Column     | Description                                                                                        |
| ---------- | -------------------------------------------------------------------------------------------------- |
| instant    | A unique sequential ID number for each row                                                         |
| dteday     | The date of the rentals                                                                            |
| season     | The season in which the rentals occurred                                                           |
| yr         | The year the rentals occurred                                                                      |
| mnth       | The month the rentals occurred                                                                     |
| hr         | The hour the rentals occurred                                                                      |
| holiday    | Whether or not the day was a holiday (0:not holiday ; 1: holiday)                                  |
| weekday    | TThe day of the week (as a number, 0 to 7)                                                         |
| workingday | Whether or not the day was a working day                                                           |
| weathersit | The weather (as a categorical variable)                                                            |
| temp       | The temperature, on a 0-1 scale                                                                    |
| atemp      | The adjusted temperature                                                                           |
| hum        | The humidity, on a 0-1 scale                                                                       |
| windspeed  | The wind speed, on a 0-1 scale                                                                     |
| casual     | The number of casual riders (people who hadn't previously signed up with the bike sharing program) |
| registered | The number of registered riders (people who had already signed up)                                 |
| cnt        | The total number of bike rentals (casual + registered)                                             |

Our purpose in this project is to predict the total number of bikes people rented in a given hour. You'll predict the cnt column using all of the other columns, except for casual and registered. To accomplish this, you'll create a few different machine learning models and evaluate their performance.