# Al-Agents-using-HuggingFace-s-SmoIAgents

This repository contains Python code that utilizes the smolagents library to perform a variety of tasks, including simple calculations, data fetching from the web, and visualizations. The code also demonstrates how to create a custom tool for interacting with the Hugging Face Hub.

Setup
To run this code, ensure you have the necessary libraries installed. You can install them using the following commands:

!pip -q install smolagents
!pip -q install litellm

 <h4> Environment Variables
Set your Hugging Face and OpenAI API keys as environment variables to authenticate and access their services:
 </h4>
<h3> import os
os.environ['HF_TOKEN'] = 'your_token'
 <br>
os.environ['OPENAI_API_KEY'] = 'your_openai_api_key_here'
</h3>

<h2>Code Overview
Initialization:</h2>

The code initializes a HfApiModel and a CodeAgent to carry out various tasks.
Basic Tasks:

Perform arithmetic calculations, such as 24 * 33.
Fetch information from the web, like the real name of WWE's Roman Reigns, using the DuckDuckGoSearchTool.
Data Fetching and Visualization:

Retrieve historical stock prices for Google from 2020 to 2024 and create a line graph using pandas, requests, bs4, matplotlib, and yfinance.
Custom Tool:

Define a custom tool, HFMode1DownloadsTool, to identify the most downloaded model for a specific task on the Hugging Face Hub.
<h2>What This Code Can Do</h2>
. Arithmetic Operations: Automate basic calculations.
<br>
. Information Retrieval: Use DuckDuckGoSearchTool to fetch answers from the web.
<br>
.Financial Data Analysis: Fetch and visualize historical stock data.
<br>
. Custom Tool Creation: Extend functionality by building custom tools, like fetching top models from Hugging Face.
<br>
. Data Visualization: Generate graphical representations of data to uncover trends and insights.
<br>
 .Web Scraping and API Usage: Incorporate web scraping and API calls to gather and process external data.
<br>
 <h2>Usage </h2>
This repository is a versatile starting point for automation, data analysis, and custom tool development using Python. It is ideal for:

. Developers looking to automate repetitive tasks.
<br>
. Data scientists interested in fetching and visualizing financial data.
<br>
. Enthusiasts wanting to explore custom tool creation and API interactions.
<br>
<h2>License </h2>
This project is open-source and available under the MIT License.
