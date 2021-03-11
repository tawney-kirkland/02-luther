This repo is for Metis project 2 - Luther

# Project Title
Predicting domestic movie sales prior to movie release

## Background

* The movie industry is facing stiff competition. There has been an overall downward trend in theater attendance since 2001, and an ongoing increase in Netflix’s US subscriber base.

* In this environment, studios are facing the question of which movies should go straight to theatre versus which can go direct to streaming. At the same time, theatres are facing declining attendance and potential consolidation, and need to understand which movies are worth showing based on expected performance.


## Objective

Against this backdrop, the project aims to enable the movie industry to effectively respond to the changing environment. The objective is to Develop a model that can predict domestic gross revenues prior to movie release.


## Methods
* **Desktop review** of existing literature on trends in the movie theatre and streaming industries
* **Interviews** with individuals in industry to understand trends, develop features and validate findings
* **Exploratory data analysis** on [BoxOffice Mojo](https://www.boxofficemojo.com/?ref_=bo_nb_cso_mojologo) and [The Numbers](https://www.the-numbers.com/movie/budgets/all) 
* **Predictive analysis** using linear regression

### Features
* Budget
* Sequel
* MPAA rating
* Horror
* Runtime
* Year
* Top 50 director

### Target
* Domestic gross revenue

## Findings

* Approximately 39% of revenue variance can be explained by the model, as evidenced by the R squared of 0.393. This was consistent across train, val and split.

## Insights

* High budget, high revenue - save the blockbusters for theatre release
* Low budget sequels do not fare as well at the box office as higher budget sequels - send to streaming or reconsider production when a larger budget is available
* Lower budget horrors have high returns - worth studios investing in as it is a comparatively low entry cost with a high payoff


## Tools Used
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit learn
* Beautiful Soup
