# slack-bot

Learning to build a Slack Bot, and implement it in dbt-llm-tools project so that the user can ask for the data within the slack instead of current streamlit interface

# pip-dependencies

    pip install flask slackeventsapi slackclient python-dotenv 

# rough procedure : 

 1. intialise the bot with the "app.py" to have the basic actions like replying to your "hello" message.
 2. make a ".env" file in the same directory as the "app.py" to save the token and the signing key.
 3. setup your ngrok server with the same port as is "app.py" , 3000 here.
 4. for /commands , setup the commands from the api.slack.com in the slash commands section,
    and define the function for the same.