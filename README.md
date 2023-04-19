# online-Shopping-telegram-bot
This code is a Python script for a Telegram chatbot that allows users to browse through different categories of products and make payments for the products they like. Here is a brief summary of the code:

1)The necessary modules and API keys are imported at the beginning of the script.

2)A start() function is defined that sends a welcome message to the user and displays two buttons for the user to choose from - "Categories" and "Support".

3)A message_handler() function is defined that responds to user messages depending on whether the user selects "Categories" or "Support". If the user selects "Categories", the bot displays a list of product categories. If the user selects "Support", the bot asks the user what they want.

4)A donate() function is defined that allows users to make payments for products they like. The bot sends an invoice to the user with the details of the product, and the user can choose to pay or not.

5)A query_handler() function is defined that responds to user queries when they select a product category. The bot fetches the first product in the selected category from a public API and displays its details - title, image, and description. The bot also asks the user if they like the product and want to make a payment.

6)The script sets up a webhook to listen for incoming messages from Telegram and passes the messages to the appropriate handler functions.

Overall, this script demonstrates the use of Telegram's bot API to build a simple chatbot with payment processing capabilities.
