# Documentation
## Structure of the repository

#### 1) Repository.pdf
List of all 150 repositories used in this study, along with their GitHub repository link.
These repositories are taken from RapidRelease dataset by using “Random Sampling”.
#### 2) Pull_Requests_in_Rapid_Release.csv
- All the metadata related to the study.
- Quantitative results for all the research questions, for each repository is stored in
this .csv file.
- Metadata for each repository is as follow:
a) Primary Programming Language
b) Domain
c) Number of Stars
d) Number of Forks
e) Number of Contributors
f) Releases (till 10th Jan 2020)
#### 3) Folder: Log_Files
a) Stores all the pull-requests data of each repository in the .csv format.
b) Each log file represents pull-request data for one repository.
c) Pull-requests data is as follows:
i) Pull-Request Title
ii) Closing Data
iii) Status of a pull-request: Merged/ Closed
iv) Pull-Request Id
v) Number of Lines Added
vi) Number of Lines Deleted
vii) Number of Files Changes
viii) Types of Files changes (only file extension)
#### 4) Folder: Figures
Consists of all the figures used in the paper named “An Empirical Study of Pull Requests
in Rapid Release Projects.
#### 5) Folder: Graphs
Time-series graphs.
There are 3 graphs generated for each repository. These graphs are as follows:
a) DateTime vs. File Change
b) DateTime vs. Lines Added
c) DateTime vs. Lines Removed
These graphs show activity of merged pull-requests from the start of the repository till
the first week of Jan 2020. The graphs help us to divide repository into 3 categories:
Left-skewed, Right-skewed and Symmetrical Distribution