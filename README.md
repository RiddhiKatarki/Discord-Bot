# Discord-Bot
Discord Bot which tracks transactions on the Ethereum blockchain.
Built using Python , Flask and Replit.

This Python script establishes a webhook-based service to monitor events occurring on the Ethereum blockchain and send prompt notifications to a designated Discord channel. It employs the Flask framework to create a web application, initializes the application to listen for POST requests on the /notify route, and retrieves the Discord webhook URL from an environment variable. The notify function processes JSON data containing Ethereum blockchain event information, constructs descriptive messages about these events, and dispatches these messages to the Discord channel through a webhook. The script's execution starts the Flask app to operate on all available network interfaces and port 81, ensuring seamless event monitoring and timely notifications.
