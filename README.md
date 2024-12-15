# BasketballProject


Dickinson Men's Basketball: Season and play-by-play analysis <br>
![Dickinson Athletics logo](dickinsonathleticsimage.jpeg) <br>

## Introduction
We were given access to the Dickinson College Men’s Basketball account with Synergy Sports. <br>
With this, we were able to access *event level*, *game level*, and *season level* data.

## Data Retrieval
The process to get the data out of the website varied based on the type of data. The **season level** data for individual players and as a team was easily downloaded as a PDF and then converted to a CSV in Excel which could be read into Python. The **event level** data was more difficult to access. We had to inspect the elements of the page and find the login token as well as the link to the data. Then in Python, we were able to just switch game IDs to use that link and token to have requests collect the data and then we specified what elements to pull out of the mass list and into the data frames we would create. 


| Data File Name  | Data.Files | Link to File |
| -- | -- | -- | 
| “Seasondata” | seasondata.csv | <a href="seasondata copy.csv">Download Season Data CSV File</a> |
| “All games” | all_games.csv | <a href="all_games copy.csv">Download All Games CSV File</a> |

## Processing the Data



