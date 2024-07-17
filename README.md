Installation

Prerequisites:
1. Python 3.x (https://www.python.org/)
2. asyncio library (pip install asyncio)
3. pyppeteer library (pip install pyppeteer)
4. google-generativeai library (https://pypi.org/project/google-generativeai/)

____________________________________________________________________________________________________________________________________________________________________________________________________________
   
Installation:
Clone this repository: git clone https://github.com/your-username/your-repo-name.git
Install the required libraries: pip install -r requirements.txt (assuming you have a requirements.txt file listing dependencies)
Usage

____________________________________________________________________________________________________________________________________________________________________________________________________________

Obtain an API key:

Refer config.py

____________________________________________________________________________________________________________________________________________________________________________________________________________

Create a configuration file:

Create a Python file named config.py in the project's root directory.
Add the following line, replacing YOUR_API_KEY with your actual API key:
Python
API_KEY = "YOUR_API_KEY"
Use code with caution.

____________________________________________________________________________________________________________________________________________________________________________________________________________

Run the script:

Open a terminal or command prompt and navigate to the project directory.
Execute the following command:

Command Prompt
--python summarizer.py

Use code with caution.
You will be prompted to enter the URL of the website you want to scrape reviews from.

____________________________________________________________________________________________________________________________________________________________________________________________________________

Output

The script will scrape reviews from the specified URL using a headless browser.
It will then use Google's AI Platform Natural Language API to summarize the reviews, highlighting positive and negative aspects as well as popular items mentioned.
The summary will be printed to the console.

____________________________________________________________________________________________________________________________________________________________________________________________________________

![Reviews](https://github.com/AryanGithub000/G-Maps_Reviews_Summarizer/blob/main/Reviews_2.png)

