<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Gender and Racial Diversity in the Film Industry
*Alba Balcells Vallverdú*

*Data Analytics Barcelona, June 2020*

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Dataset](#dataset)
- [Organization](#organization)
- [Links](#links)

## Project Description
The Academy Awards –popularly known as The Oscars– capture the attention of media all over the world every year. In recent ceremonies a growing debate has been set on the lack of representation of women and people of color in the awards, with the hashtag #OscarsSoWhite flooding social media. In this paper I aim to analyze the gender and racial diversity in the film industry in the United States through an analysis of the awards. The first part of the project focuses on the demographics of the nominees and winners throughout history, while a second part looks at the dialogues of the films nominated for *Best Picture* in the years 1989, 2015 and 2017. 

## Questions & Hypotheses
With the elaboration of this project I intend to answer the following questions:
- Is the gender and racial representation in the Academy Awards representative of the demographic of US population?
- How has the gender and racial representation varied throughout the years?
- Are there demographic factors influencing the probability of a nominee winning the award?
- Is there a relationship between the award category and the demographics of the nominees?
- How diverse are major speaking roles in films nominated in the Academy Awards?


## Dataset
- [The Oscar Award](https://www.kaggle.com/unanimad/the-oscar-award): Dataset containing all nominees in the Academy Awards (1929-2020).
- Web scraping of the following Wikipedia pages, containing information on Academy Awards' nominees by demographics: 
    - [All female nominees in the Academy Awards](https://en.wikipedia.org/wiki/List_of_female_Academy_Award_winners_and_nominees_for_non-gendered_categories)
    - [All black nominees in the Academy Awards](https://en.wikipedia.org/wiki/List_of_black_Academy_Award_winners_and_nominees)
    - [All asian nominees in the Academy Awards](https://en.wikipedia.org/wiki/List_of_Asian_Academy_Award_winners_and_nominees)
    - [All latin american nominees in the Academy Awards](https://en.wikipedia.org/wiki/List_of_Latin_American_Academy_Award_winners_and_nominees)
    - [All hispanic nominees in the Academy Awards](https://en.wikipedia.org/wiki/List_of_Hispanic_Academy_Award_winners_and_nominees)
- [US census](https://www.census.gov/quickfacts/fact/table/US/PST045219): Dataset containing US population estimates (July 1, 2019)
- [Actor metrics](https://github.com/BuzzFeedNews/2018-03-oscars-script-diversity-analysis/tree/master/data): Dataset containing information on the dialogue of the films nominated for *Best Picture* in the years 1989, 2015 and 2017. The dataset includes the count of word and sentences of all characters speaking more than 100 words, as well as the gender and race of the actor that portrays it. 


## Organization
The repository contains 5 notebooks including all the cleaning and exploration process (stored in the folder *project*), as well as one final notebook containing the Final Paper for the project:  
- [Data Cleaning US census](https://github.com/albabalcells/Gender-and-Racial-Diversity-in-the-Film-Industry/blob/master/project/Data%20Cleaning_US%20census.ipynb): Cleaning of *US census* dataset
- [Data Cleaning Academy Awards](https://github.com/albabalcells/Gender-and-Racial-Diversity-in-the-Film-Industry/blob/master/project/Data%20Cleaning_Academy%20Awards.ipynb): Cleaning of *The Oscar Award* dataset and merging with datasets from web scraping of the wikipedia pages. Elaboration and exportation of *demographics* dataset, which stores the nominees and winners by gender and race, by year. 
- [Data Cleaning Movie Scripts](https://github.com/albabalcells/Gender-and-Racial-Diversity-in-the-Film-Industry/blob/master/project/Data%20Cleaning_Movie%20scripts.ipynb): Cleaning of *Actor Metrics* dataset
- [Data Exploration Academy Awards](https://github.com/albabalcells/Gender-and-Racial-Diversity-in-the-Film-Industry/blob/master/project/Data%20Exploration_Academy%20Awards.ipynb): Exploration of *The Oscar Award* and *demographics* dataset.
- [Data Exploration Movie Scripts](https://github.com/albabalcells/Gender-and-Racial-Diversity-in-the-Film-Industry/blob/master/project/Data%20Exploration_Movie%20Scripts.ipynb): Exploration of *Actor Metrics* dataset
- [Final Paper](https://github.com/albabalcells/Gender-and-Racial-Diversity-in-the-Film-Industry/blob/master/Final%20Paper.ipynb): Final Paper containing the main insights from the analysis. For a more detailed approach, look at the *Data Exploration* notebooks. 

The raw and cleaned data used is stored in the folder *data*. 

## Links

[Repository](https://github.com/albabalcells/Gender-and-Racial-Diversity-in-the-Film-Industry)  
[Slides](https://drive.google.com/file/d/1ToVfVANirEMRr2n7gYQB75PR7nZFfcE8/view?usp=sharing) 

