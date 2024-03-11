# WhatsApp Bot with Python and Meta Cloud API

This guide helps you create a WhatsApp bot using the Meta (formerly Facebook) Cloud API with pure Python and Flask. It includes integration with webhook events for real-time message handling and utilizes OpenAI for AI-generated responses. 

## Prerequisites
- Meta developer account: [Create one here](https://developers.meta.com/)
- Business app: [Learn to create a business app](https://developers.meta.com/docs/whatsapp/getting-started#create-a-business-app)
- Familiarity with Python

## Table of Contents
- [Get Started](#get-started)
- [Select Phone Numbers](#step-1-select-phone-numbers)
- [Send Messages with the API](#step-2-send-messages-with-the-api)
- [Configure Webhooks to Receive Messages](#step-3-configure-webhooks-to-receive-messages)
- [Testing the Integration](#testing-the-integration)

## Get Started
1. **Overview & Setup**: Begin your journey here.
2. **Locate Your Bots**: Find your bots here.
3. **WhatsApp API Documentation**: Understand the official documentation.
4. **Helpful Guide**: A Python-based guide for sending messages.
5. **API Docs for Sending Messages**: Check out the documentation.

## Step 1: Select Phone Numbers
- Make sure WhatsApp is added to your App.
- Begin with a test number for sending messages.
- Go to API Setup to add numbers to send messages to.
- Verify your number via WhatsApp.

## Step 2: Send Messages with the API
- Obtain a 24-hour access token from the API access section.
- Convert the curl command to a Python function with the `requests` library.
- Create a `.env` file based on `example.env` and update required variables.
- Expect a delay of 60-120 seconds for the "Hello World" message.
- Extend access beyond 24 hours by creating a system user.

## Step 3: Configure Webhooks to Receive Messages
- Launch ngrok for secure internet exposure.
- Integrate ngrok URL in the Meta App Dashboard for WhatsApp Configuration.
- Subscribe to message fields and test the integration.

## Testing the Integration
- Use your WhatsApp product number or the test number.
- Send a message to your WhatsApp bot.
- Confirm the Flask app receives and logs the message.
- Test if the bot replies in uppercase.

You have now successfully integrated the bot! 🎉 Time to build amazing things with it.
