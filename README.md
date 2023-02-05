# SalaryRegressionPredictor
A **linear regression** model done with data from a quiz for salaries in the IT community in Bulgaria.

## Dependencies
To start you will need:
* Jupyter Notebook
* Numpy
* Pandas
* Sklearn

## Technology
Just a simple **linear regression** model. It calculates coefficients based on the independent variables you feed it and an intercept.

Then it uses a simple formula which looks something like this:

`prediction = m1 * coefficient[0] + ... + mN * coefficient[N-1] + intercept`

## Purpose
This model uses data from a quiz done in the Bulgarian IT community. The purpose is to be able to predict salary based on years of experience in the current tech stack and years of experience overall.

## Motivation
Experience in ML and interest in the topic of salaries in the IT community in Bulgaria.

## Usage
_To use just write `regression.predict([[<starting_salary>, <current_experience>, <overall_experience>, <people_you_manage>, {1/0 for the position you are working on}]])`_

_Also you can find the exported model in the file `salaries_model`. To load you just use `joblib` or `pickle`._

## The quiz
Useful links:
* The actual quiz link is this: https://forms.gle/zMqwvoeBd8f1FR4KA
* The data I used was downloaded from here: https://docs.google.com/spreadsheets/d/1HlwvgpJi5Nh4kf3FRbr86Tnx6fT7HQ1nF8eahfQZVkY/edit#gid=318991864
## Notes
* With the last updates (_v. 0.1.0_) the model has a score of **83%** which makes it pretty believable;
* Could be changed in the future as I am learning new things and becoming better at the subject;

## Version
The version will be incremented on major changes.

_v. 0.1.1_
