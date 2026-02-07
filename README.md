# Sales Summary Automation

This project is an n8n workflow that automatically monitors a Google Sheets file for new sales orders, generates a clean summary using OpenAI, and sends the summary to the team via email.

## How It Works

1. Google Sheets Trigger  
   The workflow checks a Google Sheets document for new or updated order rows.

2. AI Summary (OpenAI)  
   Order details such as customer name, product, quantity, price, and status are summarized into a professional email format.

3. Email Notification (Gmail)  
   The generated summary is sent automatically to the team via Gmail.

## Order Information Used

- Order ID  
- Customer Name  
- Product  
- Quantity  
- Price  
- Order Date  
- Status  

## Output

The AI generates:
- Email Subject
- Email Body

Each email is signed as:
Customer Success Team

## Requirements

- n8n
- Google Sheets account
- Gmail account
- OpenAI API key

## Use Case

This automation is useful for sales teams and customer success teams who want instant email summaries of new orders.

## Status

The workflow is currently inactive and can be enabled from the n8n dashboard.
