# KeplerExoplanets

## Presentation

### Selected topic
### Reason why the topic has been selected
### Description of the source of data
### Questions we hope to answer with the data

## GitHub
### Communication protocols
After each pull request (PR), the person in charge of the github repository will review the code and ask for team assistance if necessary.
![review_process.png)](images/github/review_process.png)

After the PR has been accepted, the person who made the PR will merge her/his code to the main branch and alert the team that their own personal branch or sub-branch needs to be updated with the latest version of the main branch.
![github_merge.png)](images/github/github_merge.png)


## Machine Learning Model
At the moment our target result is binary: Is it a planet or not. 
The dataset is labeled (koi_pdisposition) and so we will apply a supervised ML logistics model.<br>

Additionally our plan is to create a neural net with the sigmoid activation function and compare it to the supervised ML model.

During the initial EDA its been relaved that (koi_disposition) may be another target worth investigating. The is not binary but has (4) possible outcomes.<br>
Also during EDA we discovered that there are a large number of NaN values that we will need to process.

For the initial model we have removed all NaNs.

## Database

## Dashboard
