# OIM7502 Midterm

## Documentation:

1. https://selenium-python.readthedocs.io/index.html

# Instructions for Installation:

## Installing a WebDriver

A WebDriver is a tool or component of Selenium that acts as a bridge between your Selenium script and the web browser you want to utilize. WebDrivers are browser-specific, meaning you need a different WebDriver for each browser you want to automate (Chrome, Safari, Edge, etc). These WebDrivers interact with the corresponding browsers, enabling Selenium scripts to execute commands and perform actions.

1. Identify the Browser Version: Determine the version of the web browser you want to automate (e.g., Chrome, Firefox). You can usually find the browser version in the browser's settings or about section.
2. Go to the official website for the WebDriver corresponding to your browser. These can typically be found by a quick google search.
3. Download the file onto your computer and place it in a location easy to reference.

## Installing Selenium:

Assuming the user already has Python installed, the only necessary step is to run the following pip command:

1. pip install selenium

Afterwards, the user can import the library whenever it is needed by running the following lines of code:

1. from selenium import web driver
2. from selenium.webdriver.common.keys import Keys
3. from selenium.webdriver.common.by import By
4. driver = webdriver.Chrome() (Users can change the browser code to whichever they typically use).

In some cases, it is necessary to add the path to the web driver file inside the parenthesis for the code above to work properly.

## Overview of Selenium:

Selenium provides a suite of tools for automating web browsers across many platforms. The core component of Selenium is the WebDriver, which provides a platform- and language-neutral interface that allows programs and scripts to interact directly with a web browser. Selenium WebDriver supports multiple programming languages including Python, Java, C#, etc.

Some key functionalities of Selenium include:

1. Automating Web Browsers: You can write scripts to automate interactions with web browsers. This includes tasks like clicking buttons, filling forms, navigating through pages, and extracting data.

2. Headless Browser Support: Selenium supports headless browser testing, where the browser runs without a graphical user interface. This is useful for running tests in environments where a display server is unavailable or for speeding up test execution.

3. Web Scraping and Data Extraction: Selenium can be used for web scraping tasks, where you extract data from websites. It provides powerful tools for locating elements on a webpage and extracting information from them.

4. Cross-Browser Testing: Selenium allows you to run tests across different browsers such as Chrome, Firefox, Safari, and Internet Explorer, ensuring your web application works consistently across all platforms.

## Selenium for Data Science:

In the context of data science, Selenium can be particularly useful for tasks such as:

1. Web Scraping: Gathering data from websites for analysis. This can include scraping product information, news articles, social media data, etc.

2. Data Collection and Integration: Automating the process of collecting data from web-based sources and integrating it into your data pipeline.

3. Testing Data-Driven Applications: Automating the testing of web-based data-driven applications, ensuring data integrity and consistency.

4. Monitoring and Reporting: Automating the process of monitoring web data for changes and generating reports based on predefined criteria.
