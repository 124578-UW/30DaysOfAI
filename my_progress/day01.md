Day 1 - starting the 30 Days of AI challenge.

I started Day one content by reading the markdown file. The goal was to establish a connection between snowflake database and the streamlit app. This involved creating an account on snwoflake with a free trail of 120 days, and with a credit of 400 USD to complete the #30DaysofAI challenge. I read briefly about Streamlit and what it actually does, Streamlit is an open source python library that helps to create and share custom apps for machine learning and data science. I then proceeded to fork the repository and clone it on my local, and ran the app/day01.py file to validate if the connection is established. The resources mentioned in the article also brief about the importance of storing secrets like API keys, Passwords, Usernames, and Session tokens. Snowpark is a library that helps for querying and processing data in a data pipeline by providing an intuitive API. 

Day 2 

for the Day 2 challenge the goal is to run an LLM(large Language Model) cortex in snowflake. I installed a packaage for this snowflake-ml-python inside stremlit. The LLM has to get the User's input and also generate a response. I skimmed the code blocks of app/day02.py, and could see how effortless it is to create a button or an iput block on streamlit that helps with User friendly UI. The LLM uses the AI_complete function from snowpark to generate the response. 
The prompt I used: what is the capital of India?
The response I got: New Delhi is the capital city of India. It is located in the northern part of the country and serves as the seat of the Indian government. New Delhi is part of the larger metropolitan area of Delhi.

Day 3 

The goal of Day 3 is to run snowflake cortex LLM using the snowflake.cortex complete python API. It allows the user select a model, enter a prompt and generates response. It streams the response. With streaming the words are seen immediately. Streaming matters because it will make the app feel more responsive and quick even if it takes the same time. 