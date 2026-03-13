# Accuracy Test Report

## Project Title
Real-Time Currency Converter Chatbot

## Objective
To test the chatbot's accuracy in handling currency conversion requests and invalid inputs.

## Test Cases

| Test Case ID | User Input | Expected Result | Actual Result | Status | Comments |
|---|---|---|---|---|---|
| TC01 | convert 20 EUR to USD | Chatbot should return the correct USD equivalent of 20 EUR |  |  | Standard valid input |
| TC02 | convert 50 GBP to USD | Chatbot should return the correct USD equivalent of 50 GBP |  |  | Standard valid input |
| TC03 | convert 100 USD to CAD | Chatbot should return the correct CAD equivalent of 100 USD |  |  | Standard valid input |
| TC04 | convert 100 usd to cad | Chatbot should still work because currency codes are converted to uppercase |  |  | Lowercase currency test |
| TC05 | convert 100usd to cad | Chatbot should reject the input and show format guidance |  |  | No space between amount and currency |
| TC06 | convert ten USD to CAD | Chatbot should reject the input and show format guidance |  |  | Invalid amount |
| TC07 | hello | Chatbot should reject the input and show format guidance |  |  | Invalid query |
| TC08 | convert 100 USD CAD | Chatbot should reject the input and show format guidance |  |  | Missing “to” |

## Chatbot Test Results

The screenshot below shows the chatbot responses for several test cases.

![Chatbot Test Results](chatbot-test-results.png)
