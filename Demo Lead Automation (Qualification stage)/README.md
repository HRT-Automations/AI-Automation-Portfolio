# Lead Conversion Automation (Qualification stage)
  Automatically qualify customers and let this AI Agent decide for you which ones to focus on 

## What this automation does
  This automation qualifies the customer by:
  - Detect new customer bookings
  - Process customer information
  - AI Agent qualifies customer based on information
  - Emails get sent out to team based on "lead_score" and categorized as:
    - Emergencies
    - High-Value
    - Medium-Value
    - Low-Value

## Who this is for
  - Electricians
  - Plumbers
  - Real estate agents
  - service based businesses that are overloaded with customer requests and have KPI targets to hit

## Key features
  - CRM Integration
  - AI powered qualification agent
  - Customers queries or requests get categorized
  - works 24/7 with no manual input
  - Instant emails get sent to team

## How it works
  1) Google Sheet or CRM gets updated on new bookings
  2) Customer information is gathered into workflow
  3) AI Agent qualifies customer and gives a lead_score based on your preferations
  4) Customer is categorized into 4 sections
    - Emergencies, High-Value, Medium-Value, Low-Value
  5) Emails get sent out team regarding bookings and customer info

## Tech Stack
  - n8n (workflow automation)
  - OpenAI chat model (gpt-5-mini)
  - Gmail (communication channel)
  - Google sheets (lead storage)
