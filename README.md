# Research Project: Analysis of Voter ID News Media Coverage
## Project Summary:
This repository contains notebooks and scripts for analyzing news coverage of voter ID laws in the United States, exploring variations in media discourse and its correlation with elite framing on the issue.
Despite the rare occurrence of voter fraud by impersonation and significant partisan divisions among political elites regarding voter ID requirements, there exists broad bipartisan support for such laws among the American public. Through computational content analysis techniques, we analyze news coverage spanning a decade to explore how different media outlets frame the issue. Our findings reveal variations in coverage based on the political leanings of the outlets and highlight a correlation between news media discourse and elite framing. Notably, we observe a significant impact of false voter fraud allegations on left-leaning media coverage, potentially contributing to the amplification of electoral conspiracies instead of presenting alternative perspectives on voter ID laws.

## Project Files

| File Name                                     | Description                                                                                        |
|-----------------------------------------------|----------------------------------------------------------------------------------------------------|
| Preprocessing-corpus_2.ipynb                 | Notebook containing preprocessing steps for corpus data                                             |
| articlecount-bymonth.ipynb                   | Notebook for counting articles by month                                                            |
| data-download-LexisNexisTools.Rmd            | R Markdown file for downloading data using LexisNexisTools                                           |
| data-merge-corpus-mediacloud-nexisuni-newdata.Rmd | R Markdown file for merging data from MediaCloud and NexisUni                                   |
| mediacloud-url-prep.ipynb                    | Notebook for preparing URLs for MediaCloud                                                          |
| networks_fileprep_headlines.ipynb            | Notebook for preparing headline data for network analysis                                            |
| networks_fileprep_title.ipynb                | Notebook for preparing title data for network analysis                                               |
| tfidf_bymonth.ipynb                          | Notebook for calculating TF-IDF by month                                                             |
| url-download-NewsPlease - new data.ipynb     | Notebook for downloading data using NewsPlease                                                       |
| wordembeddings_left.ipynb                    | Notebook for generating word embeddings from left-leaning sources                                    |
| wordembeddings_right.ipynb                   | Notebook for generating word embeddings from right-leaning sources                                   |

## Data Availability:
Please note that while the analysis code and methodology are provided in this repository, the actual news media content used for analysis is not available due to copyright restrictions. The dataset used in this study includes headlines, publication dates, and other metadata extracted from various news sources. However, the full text of the articles is not included to comply with copyright laws. Researchers interested in replicating or extending this study may obtain access to the original news articles through licensed sources or by contacting the respective news organizations directly. We have provided detailed documentation on data collection methods and preprocessing steps to facilitate reproducibility and transparency in research.
