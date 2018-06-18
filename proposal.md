Freestyle Final Project

Author: awalfrand

# Project Planning
## Problem Statement

For my final project, I would like to help solve for the complexity that learning about healthcare brings. I propose creating an app that will give me different information on medications, and then linking the app user to a doctor who can help them specifically with that medication. I would also like the app to have a “compare me” feature, where a user can look at two drugs side by side and compare them on key attributes. 

## Information Requirements

For this app, I will need information on various drugs and what those drugs are used to treat. I will also need information on doctors in the area, so that I may match up the doctors’ specialties with those looking to get information on the issue that the drug they searched for is looking to treat.

### Information Inputs

The user would have to put in the name of the drug that they are looking to get information on. Depending on the information provided in the API, it would be idea for them to have the ability to search by either brand or generic name. 

If a user is comparing two drugs, they would need to put in both names at the same time to receive a comparison.

Lastly (depending on the data from the API), the user will need to enter their zip code to find a doctor close to them that specializes in the issue the drugs are trying to treat. 

###Information Outputs

Depending on the data available in the APIs, once a user enters their input, I’d like for the app to provide a variety of information regarding the drug (or drugs) that they are looking to get information on, including (but not limited to):
What it’s usually meant to treat
How long it has been on the market
Side effects

In addition, once a user enters their zip code to find a doctor, the app should be able to pull up the name and contact information of a doctor that specializes in the drug they just looked at. Depending on the information the API has, I’d like to include some kind of a rating system for the doctors, if available. 

###APIs and Web Service Requirements

I will be using an API from openFDA, which provides public FDA data on drugs.

I will also be using data from the BetterDoctor API to get information on different doctors.  

This app would be run from the command line. 

### Python Package Requirements

None identified as of yet

### Hardware Requirements

None identified as of yet
