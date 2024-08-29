<h1 align="center"> Python + Selenium </h1>

<p align="center"> Web Scraping using Selenium and Python </p>

## :rocket: About the project 

This project uses the **Selenium** library to perform web scraping on a video card page from the Kabum website. The script collects information about video cards, including image, name, and price, and saves this data to a CSV file.

## :thinking:  Why?

Just practice my skills.

## :warning: Prerequisites

Before running the script, you need to have the following installed:

- [Python](https://www.python.org/downloads/)
- [Selenium](https://pypi.org/project/selenium/)
- [ChromeDriver](https://developer.chrome.com/docs/chromedriver/downloads) (make sure the version of ChromeDriver matches your Chrome browser version)

## Code Description

- **URL**: The script accesses the URL https://www.kabum.com.br/hardware/placa-de-video-vga.
- **Selenium Configuration**: The Chrome browser is set up to run in headless mode.
- **Data Extraction**: The script collects the image `src`, name, and price of up to 20 products and saves this information in a CSV file named `Placas_Kabum.csv`.
- **Error Handling**: If the information cannot be extracted, the script prints an error message.
