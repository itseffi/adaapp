# Ada (Ask the data app)

Ada is an LLM powered app for data querying, utilizing LangChain with the Pandas DataFrame Agent and built with Streamlit.

## Demo 

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://ada-app.streamlit.app/)

## Get an OpenAI API key
You can get your own OpenAI API key by following the following instructions:
1. Go to https://platform.openai.com/account/api-keys.
2. Click on the `+ Create new secret key` button.
3. Enter an identifier name (optional) and click on the `Create secret key` button.

## Use the app
Once the app is loaded, do the following in sequential order:
1. Upload a CSV file (you can also tweak the underlying code to have it read in other tabular formats such as Excel or tab delimited files.
2. Select an example query from the drop-down menu or provide your own custom query (by selecting the *Other* option).
3. Enter your OpenAI API key.

## Features
- Natural Language Queries: Ask questions in plain english and receive insightful answers.
- Flexible Data Input: Ada works with various tabular data formats for comprehensive analysis.
- Interactive UI: Streamlit's framework ensures a user-friendly and responsive interface.

##  Todos
- Enhanced support for additional file formats.
- Advanced query options for more complex data analysis.
- Integration with other data visualization tools for more dynamic reporting.

