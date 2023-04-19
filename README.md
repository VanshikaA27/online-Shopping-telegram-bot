# online-Shopping-telegram-bot
The necessary modules and API keys are imported at the beginning of the script.

A start() function is defined that sends a welcome message to the user and displays two buttons for the user to choose from - "Categories" and "Support".

A message_handler() function is defined that responds to user messages depending on whether the user selects "Categories" or "Support". If the user selects "Categories", the bot displays a list of product categories. If the user selects "Support", the bot asks the user what they want.

A donate() function is defined that allows users to make payments for products they like. The bot sends an invoice to the user with the details of the product, and the user can choose to pay or not.

A query_handler() function is defined that responds to user queries when they select a product category. The bot fetches the first product in the selected category from a public API and displays its details - title, image, and description. The bot also asks the user if they like the product and want to make a payment.

The script sets up a webhook to listen for incoming messages from Telegram and passes the messages to the appropriate handler functions.
