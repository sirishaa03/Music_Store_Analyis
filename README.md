# Music Store Data Analysis

## Overview
This project involves analyzing a music store's database using PostgreSQL and pgAdmin. The goal is to answer a series of questions that provide insights into the store's sales, customers, and music preferences.

## Project Structure
- **SQL Queries**: A collection of SQL queries designed to answer specific questions about the music store's data.
- **Data**: The database used for analysis, which includes tables such as employees, invoices, customers, tracks, and genres.

## Database Schema
![MusicDatabaseSchema](https://github.com/sirishaa03/Music_Store_Analyis/assets/69033468/30e48469-3da1-470b-8d08-f7c07deab15d)

## Questions for Analysis
1. **Senior Most Employee**: Who is the senior most employee based on job title?
2. **Invoices by Country**: Which countries have the most invoices?
3. **Top Invoice Values**: What are the top 3 values of total invoice?
4. **Best Customers by City**: Which city has the best customers? We would like to throw a promotional Music Festival in the city we made the most money. Return the city name & sum of all invoice totals.
5. **Best Customer**: Who is the best customer? The customer who has spent the most money.
6. **Rock Music Listeners**: Return the email, first name, last name, & genre of all rock music listeners. Ordered alphabetically by email.
7. **Top Rock Artists**: Invite the artists who have written the most rock music. Return the artist name and total track count of the top 10 rock bands.
8. **Tracks Longer Than Average**: Return all track names that have a song length longer than the average song length. Return the name and milliseconds for each track, ordered by the longest songs first.
9. **Customer Spending on Artists**: Find how much each customer has spent on artists. Return customer name, artist name, and total spent.
10. **Most Popular Genre by Country**: Determine the most popular music genre for each country based on the highest amount of purchases. Return each country along with the top genre.
11. **Top Customer by Country**: Determine the customer that has spent the most on music for each country. Return the country along with the top customer and amount spent.

## Results
The results of the queries are provided in the `output_query_sheet.sql` file. Each query is designed to extract meaningful insights from the music store's database.

## Setup and Usage
1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/sirishaa03/music_store_analysis.git
   ```
2. **Set Up Database**:
  - Ensure you have PostgreSQL and pgAdmin installed.
  - Load the provided database schema and data into your PostgreSQL instance.

3. **Run Queries**:
  - Open pgAdmin and connect to your PostgreSQL database.
  - Execute the queries from the output_query_sheet.sql file to get the desired results.   

Thankyou!
