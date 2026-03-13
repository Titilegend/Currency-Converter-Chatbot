# Real-Time Currency Converter Chatbot

A simple Python chatbot that converts currencies in real time using an exchange rate API.  
The project demonstrates how to fetch live data from an API and interact with a user through a command-line chatbot.

## Features

- Convert currencies in real time
- Uses a free exchange rate API
- Simple chatbot-style interaction
- Beginner-friendly Python project
- Runs easily in Google Colab

## Technologies Used

- Python
- Requests library
- Frankfurter Exchange Rate API

## Example Usage

User input:

convert 100 USD to NGN

Output:

100 USD = 138500 NGN

## How It Works

1. The user enters a currency conversion request.
2. The program extracts the amount and currencies.
3. A request is sent to the exchange rate API.
4. The API returns the latest exchange rate.
5. The chatbot prints the converted amount.

## Running the Project

1. Open the notebook in Google Colab.
2. Install the required library:

pip install requests

3. Run the notebook.
4. Enter a query like:

convert 50 USD to EUR

## API Used

Frankfurter Exchange Rate API  
https://www.frankfurter.app


## Future Improvements

- Add a web interface
- Support more natural language queries
- Add error handling for invalid currencies
