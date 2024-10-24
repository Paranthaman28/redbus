Project Report: Redbus Data Scraping with Selenium & Streamlit Application
1. Introduction
The goal of this project is to scrape bus travel data from the Redbus website, focusing on routes, schedules, prices, and seat availability. This data will be stored in a mySQL database and presented through a user-friendly Streamlit application, allowing users to filter and interact with the data efficiently.

2. Approach
2.1 Data Scraping
Tool Used: Selenium was employed to automate the extraction of data from the Redbus website.
Data Collected: The scraping process targeted the following information:
Routes: Start and end locations of the bus journeys.
Schedules: Departure and arrival times.
Prices: Cost of tickets for various bus types.
Seat Availability: Information on available seats for each bus.
2.2 Data Storage
The scraped data was stored in a structured SQL database. This ensured efficient querying and data retrieval for further analysis.
2.3 Streamlit Application
Development: A Streamlit application was created to provide a visual interface for users to interact with the scraped data.
Features Implemented:
Filters: Users can filter data based on:
Bus type (e.g., government state buses, private buses)
Route selection
Price range
Star rating (user ratings)
Availability (seats available)
2.4 Data Analysis/Filtering using Streamlit
SQL Queries: mySQL queries were utilized to retrieve and filter data based on user inputs.
User Interaction: Streamlit's interactive components allowed users to apply filters easily, enhancing their experience.
3. Results
Data Scraping: Successfully scraped data from a minimum of 10 Government State Bus Transport providers, along with relevant private bus information for selected routes.
SQL Database: Data was stored in a well-structured SQL database, allowing for efficient data management.
Streamlit Application:
An interactive Streamlit application was developed.
Users can effectively filter and explore the scraped data.
The application is designed to be user-friendly and efficient.
4. Conclusion
This project successfully demonstrates the ability to scrape real-time bus travel data from the Redbus website, store it in a SQL database, and present it through a dynamic Streamlit application. Future work may involve enhancing the application's features and integrating additional data sources to provide more comprehensive travel information.

Next Steps
Conduct user testing to gather feedback on the application.
Explore the integration of additional bus service providers.
Optimize the mySQL database for better performance and faster queries.
