# Chatbot-EnglishPremierLeagueFootball

Designed and implemented a chatbot using Google DialogFlow CX, enabling seamless integration with live data through API calls using webhooks.  
Enhanced user interaction with visual and interactive cards, supporting multimodal communication, and incorporating a custom persona. Covered 13+ topics, providing comprehensive answers and information through the chatbot.


Steps:
1. Setup an account on [Google DialogFlow CX](https://dialogflow.cloud.google.com/cx/projects).
2. Create a new agent.
3. Import the '.blob' file to retrieve the agent.
4. Go to Webhooks and create a new Webhook with Python language and use the code in 'function-source.zip'.
5. Replace the API-KEY with your own key from [api-football](https://www.api-football.com/).
6. Copy the webhook link into your agent to connect them.
7. Now, you can test the agent using 'Test Agent' mode.
8. To set up the Web interface, get a local Python server running for the 'chatbot.html'.
9. Replace the '<script> and <df-messenger> data with the one from your agent.
10. Run the webpage and use the chatbot.
