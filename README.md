# Learn Regular Expressions by Building a Spam Filter

A simple web application that allows users to enter a message and checks if it would be marked as spam or not. The application uses regular expressions to check for certain phrases in the message.

## Getting Started

Clone the repository to your local machine and open the `index.html` file in a web browser.

### Using the Application

1. Enter a message in the text area.
2. Click the "Check message" button.
3. The application will check if the message contains any spam phrases and display a message accordingly.

### Spammer Phrases

The application currently checks for the following spam phrases:

- "please help"
- "assist me"
- "$X dollars"
- "free money"
- "stock alert"
- "dear friend"

You can add more phrases to the `denyList` array in the `script.js` file if you want the application to check for more phrases.

### Tests

The application currently has no tests. If you want to add tests, you can create a new folder called `tests` and add your test files there.

### Contributing

If you want to contribute to the application, you can create a pull request with your changes. Please make sure to explain what changes you made and why in your pull request.

### License

The application is licensed under the MIT License. See the `LICENSE` file for more information.
