
WhatsApp Bot with Python and Meta Cloud API
This guide helps you create a WhatsApp bot using the Meta (formerly Facebook) Cloud API with pure Python and Flask. It includes integration with webhook events for real-time message handling and utilizes OpenAI for AI-generated responses.

Prerequisites
Meta developer account: Create one here
Business app: Learn to create a business app
Familiarity with Python
Table of Contents
Get Started
Select Phone Numbers
Send Messages with the API
Configure Webhooks to Receive Messages
Testing the Integration
Get Started
Overview & Setup: Begin your journey here.
Locate Your Bots: Find your bots here.
WhatsApp API Documentation: Understand the official documentation.
Helpful Guide: A Python-based guide for sending messages.
API Docs for Sending Messages: Check out the documentation.
Step 1: Select Phone Numbers
Make sure WhatsApp is added to your App.
Begin with a test number for sending messages.
Go to API Setup to add numbers to send messages to.
Verify your number via WhatsApp.
Step 2: Send Messages with the API
Obtain a 24-hour access token from the API access section.
Convert the curl command to a Python function with the requests library.
Create a .env file based on example.env and update required variables.
Expect a delay of 60-120 seconds for the "Hello World" message.
Extend access beyond 24 hours by creating a system user.
Step 3: Configure Webhooks to Receive Messages
Launch ngrok for secure internet exposure.
Integrate ngrok URL in the Meta App Dashboard for WhatsApp Configuration.
Subscribe to message fields and test the integration.
Testing the Integration
Use your WhatsApp product number or the test number.
Send a message to your WhatsApp bot.
Confirm the Flask app receives and logs the message.
Test if the bot replies in uppercase.
You have now successfully integrated the bot! 🎉 Time to build amazing things with it.
