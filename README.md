# language_difficulty
Communicating data findings: What linguistic features make some languages more difficult than others?

# What makes some languages more difficult to learn than others?
## by Lauren Marar

This analysis will look at langauge difficulty for native English speakers and examine the linguistic features that distinguish easier and more difficult languages. Are there particular grammatical or phonological features that launch an otherwise ordinary language into the realm of difficult?

### This analysis merges two datasets:

1. The World Atlas of Language Structures (WALS), which catalogues language features for 2,679 languages: https://www.kaggle.com/rtatman/world-atlas-of-language-structures 


2. Language difficulty ratings as determined by the Foreign Service for 67 frequently studied languages: https://www.state.gov/m/fsi/sls/c78549.htm The difficulty levels were derived from the expected time it would take a native English speaker to reach "Professional Working Proficiency" (a score of 3 in speaking and reading on the Interagency Language Roundtable scale). English will be added as "level 0" for a comparison point.

## Data Wrangling

* The Foreign Service rating dataset required cleaning and tidying to align the language names with the WALS dataset and parse out the numerical values for duration of study and difficulty ratings.
* Because there was an unbalanced number of languages in each difficulty level, a relative frequency was generated for each linguistic feature by difficulty level.
* Finaly, because the WALS dataset included 144 linguistic features, these featured were clustered into meaningful groups, such as phonological properties and sentence structure, to better synthesize the findings.

## Summary of Findings

Many linguistic features varied by language but not necesarily by difficulty; however, there were some fairly distinct differences between English and the more difficult languages, including:

* Whether the language uses definite articles
* How the language shows the relationship between participants of an event
* Whether the language uses prepositions or postpositions
* Where the language places a relative clause with respect to the noun
* Where the language places the interrogative phrase in a question
* How the language aligns a verbal person marker
* How the language expresses a negative indefinite pronoun
* How the language forms a yes or no question
* How the language describes ownership/posession
* How the language encodes relative clauses

## Key Insights and Further Research

> There is a relationship between linguistic features and language difficulty; however, languages are so diverse that what makes one language difficult is not what makes another language difficult.
> Only 67 languages had difficulty ratings. It appears that this 67 is not representative of the world's languages (with some language familys overrepresented and others underrepresented). Only 5 of the languages had the highest difficulty rating. It would be interesting to investigate whether there are truly few languages of this difficulty level, or whether there are many difficult languages that are unrated.
> It may be worthwhile exploring the interaction between several linguistic features, to see if certain combinations create a perfect storm for language difficulty. 
