# SHEIN Order Assistant

A Telegram assistant built with n8n that helps customers place SHEIN orders by sending a product link. It collects the order details, calculates delivery, and sends the customer a final summary for confirmation.

<img width="587" height="250" alt="SHEIN Order Assistant demo" src="https://github.com/user-attachments/assets/91b64d14-9dfb-4e25-af15-224bc5511233" />

## How it works

1. The customer sends a SHEIN product link through Telegram.
2. The workflow retrieves the product page and extracts the available product details.
3. The bot asks for the customer's name, phone number, and area.
4. It calculates the delivery fee and prepares the order summary.
5. After the customer confirms, the order is saved to Google Sheets and an admin notification is sent.

## Main features

- SHEIN link handling and product information extraction.
- Step-by-step collection of customer details.
- Delivery fee calculation.
- Order summary and customer confirmation.
- Order storage and admin notifications.

## Technologies

n8n, Telegram, Google Gemini, Google Sheets, n8n Data Tables, and JavaScript.

## Setup

Import [workflow.json](./workflow.json) into n8n, configure Telegram and Google credentials, and set your Google Sheets and Data Table details.
