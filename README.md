# BigData_FinalProject
This repo is for the BIO 594 final class project. For my project, I decided to analyze data from my thesis research in R Studio, create a markdown file with the analysis, and create a research poster with some of this analysis. 

#### Description of files
AdultLobster2017_Analysis.csv : raw data file

Hoffman_BigData_Poster.pdf : poster of thesis research - brief methods and context for research can be found here

LobsterAnalysis_Markdown.Rmd : R markdown file with data analysis - brief methods and rationale for analysis found here, in addition to the actual code I used for my analysis

LobsterAnalysis_Markdown.Rmd : PDF of data analysis in R markdown


#### Description of variables in data file AdultLobster2017_Analysis.csv: 

Tag number: some individuals have 2 tag numbers because they molted and got an new tag

Sex: M (male) and F (female)

Initial size: carapace length in milimeters at beginning of experiment

NewSize: carapace length in milimeters at end of experiment

SizeChange: Change in carapace length from beginning to end of the experiment (change only occurred if the lobster molted)

Tank: tank number lobster was in for duration of the experiment

Treatment: the probiotics treatment

MoltDate: day the lobster molted (if the lobster molted during  experiment)

Molt: 0 or 1 - indicates if the lobster molted (1) or did not molt (0)

InitialSeverity: Severity of shell disease at beginning of experiment - 1 indicates if lesions covered >50% of carapace, 0 is <50%

EndSeverity: Severity of shell disease at end of experiment or when the lobster molted - 1 indicates if lesions covered >50% of carapace, 0 is <50%
