# Covid-19_Explatory-Data-Analysis
# 🦠 COVID-19 Portfolio Project Queries (PostgreSQL)

This project contains a collection of SQL queries written in PostgreSQL that analyze global and country-specific COVID-19 data, with a focus on India. The goal is to derive meaningful insights from COVID death and vaccination data using analytical SQL techniques.

## 📁 Dataset Sources

These queries are based on two primary tables:
- `CovidDeaths` – contains information such as total cases, deaths, hospitalizations, etc.
- `CovidVaccinations` – contains data on vaccination progress across countries.

> The data is sourced from [Our World in Data](https://ourworldindata.org/coronavirus-source-data).

## 🛠 Technologies
- PostgreSQL 17+
- pgAdmin or any SQL client
- Git & GitHub

## 📊 SQL Queries Overview

| Query Code | Description |
|------------|-------------|
| a | Date-wise likelihood of dying due to COVID in India (Total Cases vs Total Deaths) |
| b | Total % of deaths out of India's entire population |
| c | Verifies (b) by retrieving deaths and population separately |
| d | Country with highest death % relative to population |
| e | India's % of COVID positive cases (cases vs population) |
| f | COVID positive cases % for each country |
| g | Continent-wise total COVID cases |
| h | Continent-wise total COVID deaths |
| i | India's daily new cases vs hospitalizations vs ICU admissions |
| j | Country-wise population aged over 65 |
| k | Country-wise fully vaccinated people |
