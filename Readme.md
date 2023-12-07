# Covid-19 Data Exploration

## Project Overview

The **Covid-19 Data Exploration** project focuses on analyzing Covid-19 data using SQL queries. The skills applied in this exploration include Joins, Common Table Expressions (CTEs), Temporary Tables, Window Functions, Aggregate Functions, Creating Views, and Converting Data Types.

## Data Selection

- Selected relevant data from the `CovidDeaths` table, filtering out records where the continent is null.

## Total Cases vs Total Deaths

- Calculated the likelihood of death if contracting Covid-19 in a specific country.
- Selected data for locations containing the term 'states' in their name.

## Total Cases vs Population

- Explored the percentage of the population infected with Covid-19.

## Countries with Highest Infection Rate compared to Population

- Identified countries with the highest infection rates relative to their population.

## Countries with Highest Death Count per Population

- Listed countries with the highest death counts per population.

## Breaking Things Down by Continent

- Explored continents with the highest death counts per population.

## Global Numbers

- Calculated global Covid-19 cases, deaths, and death percentage.

## Total Population vs Vaccinations

- Analyzed the percentage of the population that received at least one Covid-19 vaccine dose.

## Using CTE to Perform Calculation

- Used a Common Table Expression (CTE) to perform calculations on vaccination data.

## Using Temp Table to Perform Calculation

- Employed a temporary table to perform calculations on vaccination data.

## Creating View for Later Visualizations

- Created a view named `PercentPopulationVaccinated` to store data for future visualizations.
