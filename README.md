# Netflix Analysis using R

This project involves analyzing the Netflix dataset using R programming language. The dataset consists of two CSV files: `show.csv` and `MaturityType.csv`. The `show.csv` file contains information on Netflix movies and TV shows, such as title, description, release date, rating, and more. The `MaturityType.csv` file contains the description of maturity type.

The analysis involves answering several questions about the dataset, such as:

- Are there any duplicate rows in the `Show` dataset? If so, how many of them and how to remove them?
- How to load the dataset into two dataframes, rename columns, and make sure date values are in the correct type?
- Which TV shows produced by a specific country are designed for "TV Show for Mature Audiences" in a specific year?
- Which production countries have the highest number of TV shows that are designed for "TV Show Suitable for General Audiences" and what are the average IMDB scores?
- How to compare the distribution of IMDB scores for movies produced after 2010 by the United States and by Canada using boxplots?
- Which are the top 5 movies suitable for children less than 7 years old based on age-appropriateness and educational value?

The analysis is done using R programming language and several packages, such as `tidyverse`, `lubridate`, and `ggplot2`.

## Requirements

To run the R script, you need to have the following:

- R programming language installed (version 4.0.5 or higher)
- RStudio Desktop installed (version 1.4.1106 or higher)
- The following R packages installed: `tidyverse`, `lubridate`, and `ggplot2`

## How to use

To run the analysis, follow these steps:

1. Download the `Show.csv` and `MaturityType.csv` files from the dataset repository.
2. Open the `Netflix.Rmd` file in RStudio.
3. Install the necessary packages by running the following code in the R console:

```r
install.packages(c("tidyverse", "lubridate", "ggplot2"))
```

4. Load the necessary packages by running the following code in the R console:
```r
library(tidyverse)
library(lubridate)
library(ggplot2)
```

5. Run each code chunk in the Netflix.Rmd file to see the analysis results.

## Conclusion


In conclusion, this project shows how R programming language can be used to analyze a dataset and answer several questions related to the dataset. The analysis includes data cleaning, data manipulation, and data visualization using various R packages. The code and results can be used as a starting point for further analysis or as a reference for similar projects.

