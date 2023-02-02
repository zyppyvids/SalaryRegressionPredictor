# SalaryRegressionPredictor
A <b>linear regression</b> model done with data from a quiz for salaries in the IT community in Bulgaria.

## Dependencies
To start you will need:
* Jupyter Notebook
* Numpy
* Pandas
* Sklearn

## Technology
Just a simple <b>linear regression</b> model. It calculates coefficients based on the independent variables you feed it and an intercept.

Then it uses a simple formula which looks something like this:

`prediction = m1 * coefficient[0] + ... + mN * coefficient[N-1] + intercept`

## Purpose
This model uses data from a quiz done in the Bulgarian IT community. The purpose is to be able to predict salary based on years of experience in the current tech stack and years of experience overall.

## Motivation
Experience in ML and interest in the topic of salaries in the IT community in Bulgaria.

## Usage
_To use just write `regression.predict([[<current_experience>, <overall_experience>]])`_

_Also you can find the exported model in the file `salaries_model`. To load you just use `joblib` or `pickle`._
