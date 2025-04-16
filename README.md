# MongoDB Stock Market Tracker

## Project Overview

This project involves designing and implementing a **MongoDB database system** to simulate a **stock market environment** with real-time price updates, historical data, transactions, market indices, and related market commentary.

It showcases MongoDB's strengths in handling high-volume, semi-structured data using advanced schema design, referencing, embedding, and indexing techniques — suitable for real-time analytics and historical performance tracking.

The purpose of this project is to:
- Practice schema design using embedded and referenced documents
- Explore MongoDB's aggregation framework
- Apply indexing and performance optimization techniques
- Simulate real-time and historical stock data analytics

---

## Collections Overview

The database contains the following key collections:

- `stocks`: Contains metadata about publicly traded companies
- `prices`: Stores daily historical stock prices
- `real_time_prices`: Tracks recent price updates in near real-time
- `events`: Records news or earnings events related to stocks
- `comments`: Allows users or analysts to leave stock-related comments

---

## Key Features

- Design of a NoSQL database schema using MongoDB best practices
- Use of both embedded and referenced documents
- Aggregation pipelines for trend analysis, moving averages, etc.
- Simulated real-time price tracking with timestamped updates
- Queryable financial events and user comment history

---

## How to Run the Project

1. **Install MongoDB**
   - [MongoDB Installation Guide](https://www.mongodb.com/docs/manual/installation/)

2. **Start MongoDB locally** or connect to **MongoDB Atlas**

3. **Import sample data**
   - Use `mongoimport` or a script to insert documents into each collection.

4. **Use MongoDB Compass or shell to run queries and aggregations**

---

## Example Use Cases

- Find the top 5 performing stocks based on average closing price
- View price trends over time for a given stock
- Filter events by date and impact level
- Analyze sentiment via user comments

---

## Technologies Used

- MongoDB
- MongoDB Compass (for UI-based data visualization)
- Aggregation framework
- JSON data structures
