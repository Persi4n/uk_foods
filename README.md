# Eat Safe, Love - NoSQL Project

## Overview
Eat Safe, Love is a food magazine that evaluates and rates food establishments across the United Kingdom. This project involves working with a MongoDB NoSQL database to manage the data related to food establishments' ratings and perform exploratory analysis.

## Project Structure
The project is divided into several parts:

### Part 1: Database and Jupyter Notebook Set-Up
- Imported the provided data from `establishments.json` into the MongoDB database named `uk_food`.
- Created a Jupyter Notebook to interact with the database using PyMongo.
- Confirmed the creation of the database, listing the collections, and assigned the `establishments` collection to a variable.

### Part 2: Update the Database
- Added a new restaurant, "Penang Flavours," to the database.
- Found the BusinessTypeID for "Restaurant/Cafe/Canteen" and updated the new restaurant with the correct BusinessTypeID.
- Removed all establishments within the "Dover" Local Authority from the database.
- Converted the data types of latitude, longitude, and RatingValue to the appropriate data types.

### Part 3: Exploratory Analysis
- Answered specific questions posed by Eat Safe, Love using MongoDB queries.
- Calculated the number of documents meeting specific criteria, displayed results using `pprint`, and converted results to Pandas DataFrames for analysis.

## Instructions for Running the Code
1. Install Python and Jupyter Notebook if not already installed.
2. Install the required Python libraries (`pymongo`, `pandas`, `decimal`).
3. Import the provided `establishments.json` data into your MongoDB database using the `mongoimport` command.
4. Open and run the Jupyter Notebook files (`NoSQL_setup_starter.ipynb` and `NoSQL_analysis_starter.ipynb`) step by step.

## Dependencies
- Python 3.x
- Jupyter Notebook
- PyMongo
- Pandas
- Decimal


