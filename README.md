# Webscraping-of-Real-Time-Weather

#### *This is a side project*

#### Collaborator: Sadhanha Anand, Cindy Jeon, Mia Lai

This project is for a business solution for Lux, an imaginary consumer electronics company. Web scraping weather data can be a solution to their business problem by allowing them to prepare for potential delivery disruptions.

**Business Scenario** : Lux's new product line targets luxury appliance buyers. Real-time weather data (OpenWeatherMap + web scraping) is used to adjust deliveries (MongoDB) to avoid extreme weather disruptions.

**Data Sources** : OpenWeatherMap ("https://openweathermap.org/")

**Web-Scraping Workflow**:

**Step 1: Autonomous Browser Interaction**

- Utilize "Selenium WebDriver" to programmatically control a web browser, enabling the team to log into websites requiring authentication and interact with web pages that load content dynamically.
- Automate the process of saving HTML pages for offline analysis and data extraction.
  
**Step 2: HTML Content Parsing**

- Implement "BeautifulSoup" for parsing and navigating the HTML content of web pages.
- Extract pertinent weather data, such as temperature, precipitation, wind speed, and weather conditions, from static web page elements.
  
**Step 3: API Integration and Data Storage**

- Identify and register for weather data APIs that provide both real-time and historical data sets.
- Systematically scrape weather data and structure it in a preliminary format, such as JSON.
- Employ MongoDB, a NoSQL database, to store and manage the scraped weather data efficiently.
