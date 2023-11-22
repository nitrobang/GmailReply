

### Project Description

This program is designed to automate responses to new unread emails and organize them by moving them to a labeled category called "OOO" The behavior of the responses is defined in a configuration file (.env), allowing customization of the email address and message content.

### Setup Instructions

1. **Create a Google Cloud Project:**
   * Begin by creating a sample app on Google Cloud.
2. **Generate Client Credentials:**
   * Create a client for the app on Google Cloud and download the client credentials.
   * Save the downloaded credentials as `credentials.json` in the root directory.
3. **Configure .env File:**
   * Update the .env file with the desired email address and the response message to be sent.
4. **Installation:**
   * Run `npm install` to install the necessary dependencies.
5. **Run Tests:**
   * Execute `npm run test` to ensure that the setup is correct.
6. **Start the Program:**
   * Run `npm run start` to initiate the program.

### Instructions for Responding to Emails

* The program will automatically check for new unread emails.
* Responses to emails will be crafted based on the message defined in the .env file.
* After responding, the emails will be organized and moved to a pre-defined label called "OOO"

### Notes for Users

* Customize the email address and response message in the .env file according to your preferences.
* Ensure proper setup and configuration before running the program.

Feel free to reach out if you encounter any issues or have further questions!
