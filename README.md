# LinkedIn Connection Automation Script Documentation

## Description
This Python script automates the process of sending connection requests on LinkedIn using the Selenium library.
It logs into your LinkedIn account,searches for a specific keyword persons, and sends a connection request to them.

## Prerequisites
- Python version: 3.6+
- Required libraries: selenium (install using `pip install selenium`)
- Web browser: Firefox (GeckoDriver executable should be available in system PATH)

## Usage
1. Run the script: `python linkedin_connection_automation.py`
2. Enter your LinkedIn username and password when prompted.
3. Provide the search key (name of the person you want to connect with).

## Script Flow
1. The script opens the Firefox web browser.
2. It navigates to the LinkedIn login page and waits for 5 seconds.
3. Enters the provided username and password.
4. Clicks the login button.
5. Searches for the provided search key (person's name, job/company title ) on LinkedIn.
6. Sends a connection request to the first person in the search results.
7. Checks if the "Connect" button is clicked and then clicks the "Send" button to send the request.
8. Repeats the connection process for other search results with "Connect" buttons.

## Important Note
- LinkedIn's user interface may change over time, which can impact the script's functionality.
  Ensure that the XPath and element locators (`by` and `value` parameters) used in the script are up-to-date.
- Use this script responsibly and follow LinkedIn's terms of use. Excessive and inappropriate use may result in account suspension.

## Author
- SHAHDAD PERVEZ SHARIF
- shahdadpervaiz@hotmail.com

## Note
- Browsers and Selenium Web-drivers are updating everyday, which results in code crash and change in parameters,
  make sure to install the compatible versions,and check the updated parameters.
