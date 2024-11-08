Examining Demographic Patterns in NYC Shooting Data
================
Team Alpha
2024-11-07

# Project Members

- **Chenhui Yan** (CY2772)
- **Zhaokun Lin** (ZL3544)
- **Mingyin Wang** (AW3693)
- **Zebang Zhang** (ZZ3309)

# Motivation

Understanding the dynamics of shooting incidents in New York City is
crucial for enhancing public safety and fostering resilient communities.
By examining demographic patterns in shooting crime data alongside
datasets on education levels, household income, and Airbnb listings, our
project aims to identify socioeconomic and housing factors that
influence gun violence. Analyzing how education disparities, income
levels, and the prevalence of short-term rentals correlate with shooting
incidents provides valuable insights for policymakers and stakeholders.
We hope our findings can assist policymakers and stakeholders in
developing targeted solutions to address the root causes of gun violence
and enhance the well-being of all New York City residents.

# The intended final products

## Descriptive Statistics

- Total shooting incidents of different boroughs within our interested
  timeframe.
- Monthly or yearly shooting incident numbers.
- Perpetrator’s sex description.
- Perpetrator’s age distribution.
- Distribution of the exact time of the shooting incident

Both descriptive statistics above can be visualized, there are lots of
other aspects that we can analyze.

## Regression

We can merged the income and education dataset to the shooting dataset,
analyze the relationship between numbers of shooting incidence of a
neighborhood and income or education level within the neighborhood.
After the regression, we’ll interpret the model and analyze the reason
behind the pattern.

## Interactive page

We’ll design a interactive page, so the website user can filter the data
in different variables(zipcode, neighborhood, borough, .etc) on the left
side of our page, after that, the filtered shooting incident will show
on a map in different dots on the right side of our page. The user can
click on the different shooting incident dots, a more detailed
information about this particular incident will shows in a small window.

# Anticipated data sources

data of the shooting incident in NYC. List of every shooting incident
that occurred in NYC going back to 2006 through the end of the previous
calendar year. Important variables: Exact date of the shooting incident
,Exact time of the shooting incident, Borough where the shooting
incident occurred, location of the shooting incident and Perpetrator’s
age within a category and Victim’s age within a category.

<https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8/about_data>

This dataset includes NYC’s househould income and median income in
different Boroughs and community districts. It also includes NYC’s
education data, including graduation rate, dropout rate, attendece and
etc.

<https://data.cccnewyork.org/data/table/1370/student-economic-status#1370/1609/127/abbr/u>

nyc airbnb dataset, important variables are the price, longitude,
latitude,

<https://insideairbnb.com/get-the-data/>

# Timeline

done data cleaning by 11/18, including merging datasets, tidy data,
finding repetative rows and etc.

11/19 - 11/30, we are going to finish the descriptive statistics,
regression, and webpage. We will also include shiny app on our website.

12/1-12/7, we are going to work on the report and the screencast, be
ready for the peer assessment.

# The planned analyses / visualizations / coding challenges

The first challenge we may encounter is in data preprocessing. For
example, in the shooting dataset, there are several columns with much
missing and invalid data. There are also some columns not useful for the
later analysis. Moreover, we have to adjust the formatting of the time
and place variable of the shooting. After the careful cleaning of every
datasets can we merge them into the final dataset that we use for
analysis.

The second challenge lies in the coding part for making the interactive
page. We need to put every dot, which represent a shooting, on a actual
and detailed map, and reach the effect that when the website user click
on a specific dot, other relevant information will show up automaticly.
What’s more, we may need to reasonably divide regions based on their
economic and educational conditions and display them in different colors
on the map. The codes may not be simple.

The third challenge may occur in visualization part. To make a plot that
can show the data patterns clearly, we need to adjust the subtle
composition elements of each plot. For example, the size of the dots on
the map, the colors used to fill graphics and the numerical intervals of
the coordinate axis. \>\>\>\>\>\>\>
c72b44f5075f9ffd2dce720ca5ce345f042518df
