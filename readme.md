# Gmail Auto-Responder Bot

This Node.js application utilizes the Google Gmail API to automatically reply to unread messages with a vacation response.

## Prerequisites

- Node.js installed on your machine
- A Google Cloud Platform (GCP) project with the Gmail API enabled
- OAuth 2.0 client credentials (client ID and client secret) for accessing the Gmail API
- Basic familiarity with Node.js and npm

## Installation

- Clone or download this repository to your local machine.
- Navigate to the project directory.
- Install dependencies using npm.
   
## Configuration

- Follow the steps outlined in the Google Developers Console to create a new project and enable the Gmail API: [Google Developers Console](https://console.developers.google.com/).
- Create OAuth 2.0 client credentials (client ID and client secret) for your project.

## Usage

- Run the application:-
- Follow the instructions in the terminal to authorize the application with your Gmail account.
- Once authorized, the application will start responding to unread messages with the vacation response.
  
## Notes

- Ensure that you have appropriate permissions to access the Gmail account from which you want to fetch and reply to messages.
- This application does not handle exceptions or edge cases comprehensively and may require additional error handling for production use.

This application was created by Vaibhav Maurya.
