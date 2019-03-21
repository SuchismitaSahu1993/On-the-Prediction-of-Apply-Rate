# Project "On the prediction of Apply Rate":

## Introduction

The problem of interest is the prediction of apply rate. Imagine a user visiting Glassdoor, and
performing a job search. From the set of displayed results, user clicks on certain ones that she is
interested in, and after checking job descriptions, she further clicks on apply button therein to land in
to an application page. The apply rate is defined as the fraction of applies (after visiting job description
pages), and the goal is to predict this metric using the dataset described.

## Dataset

Each row in the dataset corresponds to a
user’s view of a job listing. It has 10 columns as described below.
* title proximity tf idf: Measures the closeness of query and job title.
* description proximity tf idf: Measures the closeness of query and job description.
* main query tf idf: A score related to user query closeness to job title and job description.
* query jl score: Measures the popularity of query and job listing pair.
* query title score: Measures the popularity of query and job title pair.
* city match: Indicates if the job listing matches to user (or, user-specified) location.
* job age days: Indicates the age of job listing posted.
* apply: Indicates if the user has applied for this job listing.
* search date pacific: Date of the activity.
* class id: Class ID of the job title clicked.
