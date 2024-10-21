# Car Rental Price Analysis

## Project Overview
The **Car Rental Price Analysis** project is designed to help users find the best car rental deals by comparing prices across multiple car rental websites. The project uses web scraping techniques to extract data from websites such as enterprise.ca, avis.ca, and carrentals.com. By specifying pick-up and return locations, dates, and other details, the program provides users with a comparison of rental prices and highlights the best deal.

## Features
- Crawl at least three car rental websites for prices and availability.
- Compare car rental prices based on user-defined parameters such as:
  - Pick-up and return locations
  - Pick-up and return dates
  - Car categories and models
  - Additional options such as insurance
- Display the best rental deal based on the search criteria.

## Technologies Used
- **Java**: Core programming language for the project.
- **Selenium**: Used for automating web browsers to scrape car rental websites.
- **JSoup**: For parsing HTML and extracting relevant data.
- **ChromeDriver**: Driver used to run Selenium on Chrome for web scraping.
- **File Handling**: Data from the websites is stored in `.txt` files for further processing.

## Project Structure
- **chromedriver-mac-x64/**: Contains the ChromeDriver executable for macOS.
- **htmlparser/**: Directory containing code for parsing the HTML data from websites.
- **selenium-java-4.15.0/**: Selenium library dependencies.
- **src/**: Source code of the project.
- **CarRentalsX.txt**: Data files storing scraped rental information from multiple websites.
- **ExpediaX.txt**, **OrbitzX.txt**: Data files storing additional website data.
- **locations.txt**: Contains the user-specified pick-up and return locations.
- **search_frequency.txt**: Stores frequency of searches for data tracking purposes.

## Setup and Usage
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-repo/car-rental-analysis.git
