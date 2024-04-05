# Webscraping-of-Real-Time-Weather

#### *This is a side project*

#### Collaborator: Sadhanha Anand, Cindy Jeon, Mia Lai

This project is for a business solution for Lux, an imaginary consumer electronics company. Web scraping weather data can be a solution to their business problem by allowing them to prepare for potential delivery disruptions.

**Business Scenario** : Lux's new product line targets luxury appliance buyers. Real-time weather data (OpenWeatherMap + web scraping) is used to adjust deliveries (MongoDB) to avoid extreme weather disruptions.

**Data Sources** : OpenWeatherMap ("https://openweathermap.org/")

**Web-Scraping methods**:
- Step 1: Autonomous login and Configure "Selenium WebDriver" for dynamic content loading to save HTML pages
  
- Step 2: Set up "BeautifulSoup" for HTML content parsing. Useful for extracting specific information from static web pages.
  
- Step 3: Identify and register for APIs providing real-time and historical weather data, and store scraped data in a preliminary format for further processing (use MongoDB,JSON)
