# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.  In two to three sentences, describe the purpose of your survey
2.  Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.  Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios

1.  You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.  You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.  You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1.  Sample type
2.  Sample size
3.  Target population
4.  Sampling frame
5.  Survey mode(s)
6.  Timeline
7.  Response rate
8.  Weights
9.  Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used

# Your Changes

## Part A - Survey Design:

The number of your chosen topic: `3`

Describe the purpose of your survey:

```         
The purpose of this survey is to examine the relationship between age and music taste. 
The survey is designed to support two kinds of comparison: 
- Comparisons between people of different ages.
- Within-person comparisons of how a respondent's taste has changed across their own lifetime.
```

Describe your target population, sampling frame, sampling units, and observational units:

```         
Target population: 
- All adults aged 18 and older residing in Canada.

Sampling frame: 
- A national online research panel. 
- The frame is the list of panel members aged 18+ who have agreed to be contacted for research.

Sampling units: 
- Individual panel members.

Observational units: 
- Individual panel members (respondents) who report on their music preferences, which are measured at the individual level.
```

Your 5-10 question survey:

```         
1. What is your age? (in years)
   ____

2. In a typical week, about how many hours do you spend listening to music?
   ( ) Less than 1 hour
   ( ) 1–5 hours
   ( ) 6–10 hours
   ( ) 11–20 hours
   ( ) More than 20 hours

3. Which of the following genres do you currently enjoy listening to?
   (Select all that apply)
   [ ] Pop             [ ] Rock        [ ] Hip-hop / Rap
   [ ] Electronic      [ ] Country     [ ] R&B / Soul
   [ ] Jazz            [ ] Classical   [ ] Folk
   [ ] Metal           [ ] Other: ________

4. How would you describe your taste in music today compared to when you were a teenager?
   ( ) Much more focused on popular/mainstream music now
   ( ) Somewhat more focused on popular/mainstream music now
   ( ) About the same
   ( ) Somewhat less focused on popular/mainstream music now
   ( ) Much less focused on popular/mainstream music now

5. Thinking back to when you were a teenager, which genres did you most enjoy at that time?       (Select all that apply)
   [ ] Pop             [ ] Rock        [ ] Hip-hop / Rap
   [ ] Electronic      [ ] Country     [ ] R&B / Soul
   [ ] Jazz            [ ] Classical   [ ] Folk
   [ ] Metal           [ ] Other: ________
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```         
1. Sample type:
- A probability sample with a cross-sectional design, drawn using a stratified sampling design. - A two-stage selection was used: groups of telephone numbers were selected first, then one eligible individual (aged 15+) was randomly selected within each identified household.

2. Sample size:
- A field sample of approximately 50,000 units was used.
- About 40,000 invitation letters to the electronic questionnaire were sent to selected households, and a completion of roughly 24,000 questionnaires was expected/targeted.

3. Target population:
- All persons aged 15 years and older living in the ten provinces of Canada.
- Excludes full-time residents of institutions.

4. Sampling frame:
- Combination of landline and cellular telephone numbers, drawn from the Census and various administrative sources.

5. Survey mode(s):
- Self-completed electronic questionnaire (online) and computer-assisted telephone interviewing (CATI). 
- Respondents could choose between English and French. 
- No proxy responses were permitted.

6. Timeline:
- September 4, 2018 to December 28, 2018 of survey duration. 

7. Response rate:
- 41.9%.

8. Weights:
- Person-level weighting factor (WGHT_PER) is provided on the microdata file for estimating the number of persons aged 15+ with given characteristics. 
- Weights account for the probability of selection, adjust for the rejective sub-sampling of non-volunteers, and adjust for non-response. 
- Weights were also calibrated so the weighted income distribution matched the 2017 Canadian Income Survey distribution by province, so that estimates align with independent age–sex-by-province population estimates.
- Bootstrap weights were created for design-based variance estimation.

9. Data processing
- Processing used the SSPE within a structured, monitored environment. 
- Edits were performed automatically and manually at macro and micro levels and included family, consistency, and flow edits. 
- The CATI system enforced valid code ranges, built-in edits, and questionnaire flow, flagging out-of-range values during the interview.

10. Cleaning, imputation, etc:
- Imputation was carried out in nine steps and primarily used donor imputation
- Score function compared non-response (recipient) record against donor records, and the highest-scoring "nearest" donor supplied the missing value (ties broken randomly).
- Where donor imputation was not possible, mean imputation across a pool of donors was used. 
- The nine steps covered personal and family income, formal volunteering variables, informal volunteering variables, donation variables, and solicitation methods.

11. Sources of error:
- Sampling error - since estimates are based on a sample, they vary from sample to sample.
- Non-sampling error - includes coverage error, non-response, response errors, and processing errors.

12. Limitations, known biases, etc:
- Coverage bias.
- Non-response bias.
- Geographic exclusion.
- Relatively modest response rate (41.9%), increasing potential for non-response bias.

13. Link to documentation and any additional sources used:
- Survey definition, methodology and data accuracy (IMDB record 4430):
https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234
- PUMF Documentation and User Guide (Catalogue 45-25-0011):
https://www150.statcan.gc.ca/n1/en/catalogue/45250011
- The Daily release (Jan 26, 2021):
https://www150.statcan.gc.ca/n1/daily-quotidien/210126/dq210126h-eng.htm
- Questionnaire and reporting guide:
https://www23.statcan.gc.ca/imdb/p3Instr.pl?Function=getInstrumentList&Item_Id=1183690&UL=1V&
- The General Social Survey: An Overview (89F0115X):
https://www150.statcan.gc.ca/n1/en/catalogue/89F0115X
```

## Rubric

- All required components are present and complete **Complete / Incomplete**
- Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
- Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:

- Submission Due Date: `23:59 - 09 February 2026`
- The branch name for your repo should be: `assignment-2`
- What to submit for this assignment:
  - This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
- What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
  - Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist: - [ ] Create a branch called `assignment-2`. - [ ] Ensure that the repository is public. - [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them. - [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
