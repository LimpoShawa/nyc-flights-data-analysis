# NYC Flights: Exploratory Data Analysis

## Project Overview

This project explores flight data from the three major New York City airports in 2013 to understand patterns in flight activity, delays, airlines, aircraft, airports, and weather.

Using R, data wrangling, data visualization, and data-quality auditing, the analysis demonstrates how operational flight data can be transformed into meaningful insights about a complex transportation system.

## The Problem

Airports and airlines generate large amounts of operational data every day. Analysing this data can help reveal patterns in flight activity, delays, airline operations, aircraft characteristics, and other factors that affect air transportation.

This project uses the `nycflights13` dataset to explore these patterns and demonstrate how data science can be used to better understand flight operations.

## What I Did

I used R to:

* Explore and understand the structure of the flight datasets.
* Clean and transform data for analysis.
* Create visualizations to identify patterns and relationships.
* Compare flight activity across the three major NYC airports.
* Analyse departure and arrival delays across airlines and airports.
* Investigate aircraft characteristics and manufacturing years.
* Examine relationships between flights, airports, aircraft, and weather data.
* Conduct a data-quality audit to identify potentially problematic airport coordinates.
* Develop a data science question and use the available data to answer it.

## Key Findings

Some of the findings from the analysis included:

* The three airports recorded **336,776 flights** in total in 2013.
* Newark Liberty International Airport (EWR) recorded the highest number of departures among the three NYC airports.
* Average departure delays differed between the three airports.
* Airline activity and average delays varied considerably between carriers.
* **United Air Lines Inc. operated the highest number of flights**, with **58,665 flights** in the dataset.
* Aircraft characteristics, including manufacturing year and number of seats, could be explored alongside flight activity.
* The data audit identified several airport records with potentially problematic longitude values, demonstrating the importance of checking data quality before drawing conclusions.

## Why This Matters

Flight operations involve many interconnected factors, from airline schedules and aircraft characteristics to airport activity, delays, and weather.

This analysis demonstrates how data science can be used to bring these different sources of information together and identify patterns that may be useful for understanding transportation systems. In a real-world setting, similar analysis could contribute to operational monitoring, planning, resource allocation, and decision-making.

## Tools & Techniques

* **R**
* **tidyverse**
* **ggplot2**
* **Data Wrangling**
* **Exploratory Data Analysis**
* **Data Visualization**
* **Data Quality Auditing**
* **Data Joining**
* **Quarto**

## Full Analysis

The complete analysis, including the visualizations and detailed results, is available in the Quarto project.

**Files included in this repository:**

* `Project_NYCFlights.qmd` — Source Quarto document
* `Project_NYCFlights.html` — Rendered analysis
* `INSTRUCTIONS.md` — Original project instructions
* `LEARNING.md` — Learning materials
* `HOW-TO.md` — Project guidance

---

## Academic Context

This project was completed as part of my academic coursework in Data Science Concepts and Tools at Constructor University.

The project was completed using the provided course instructions and learning materials. It is published here as part of my data science portfolio to demonstrate my experience applying data wrangling, visualization, exploratory analysis, and data-quality techniques to a real-world dataset.

## License and Academic Integrity Notice

This repository is based on a Data Science Homework Project created by Jan Lorenz for teaching purposes.

The project is published in accordance with the original project instructions, which permit students to keep their completed work as a public repository in their portfolio or publish the resulting HTML, provided that the License and Academic Integrity information and the original `INSTRUCTIONS.md` are retained.

The project is intended for educational reference. Students working on similar assignments should complete their own work and follow their institution's academic integrity policies.

## Original Work Declaration

I, Limpo Shawa, worked through this project using the provided instructions and completed the analysis in my own way. Beyond the concrete instructions, I applied my own analysis, interpretations, visualizations, and data-science question to explore the NYC flight data.

## Usage Terms

This repository may be used for educational reference. Students completing similar coursework should not copy the code or analysis directly and should instead use it only as a reference while completing their own work in accordance with their academic integrity requirements.
