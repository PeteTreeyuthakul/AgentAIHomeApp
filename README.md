# AgentAIHomeMatchApp
The goal is to create a personalized experience for each buyer, making the property search process more engaging and tailored to individual preferences.

HomeMatch - Real Estate Matching Application
HomeMatch is an application that generates personalized real estate listings based on user preferences using a Large Language Model (LLM) and a vector database. This tool helps potential home buyers find properties that match their specific needs, such as location, price, amenities, and other preferences.

Features
Personalized Property Descriptions: The application customizes property descriptions based on user preferences, such as preferred location, number of bedrooms, amenities, and other features.
Top 3 Listings: The application ranks and displays the top 3 real estate listings that match the user's criteria.
Buyer Preferences Interface: Users can input their preferences, and the application will filter and personalize listings accordingly.
Prerequisites
Before running this application, make sure you have the following dependencies installed:

Python 3.x (preferably Python 3.8 or higher)
OpenAI API Key: You'll need to set up your own API key for OpenAI (if you're using GPT-3 or GPT-4) and provide it in your environment.
ChromaDB or any vector database: (if you are integrating with a vector database for storing property listings).
Libraries:
openai
pandas
numpy
requests (for API calls)
matplotlib (for visualizing data, optional)
json (for handling structured data)

How to Run the Code
1. Set up your environment:
First, make sure you have installed all the required dependencies (as mentioned above).
Create an environment variable for your OpenAI API key (or insert it directly into your code).
2. Prepare Your Listings Data:
The application expects a list of real estate listings, which can be synthetically generated or taken from a real dataset.
Save your listings in a file named listings.json. Each listing should have properties such as location, price, bedrooms, amenities, etc.
3. Input Your Buyer Preferences:
Create a dictionary containing the buyer’s preferences, such as location, budget, number of bedrooms, and desired amenities (e.g., "gym", "backyard").
4. Run the Application:
The code can be executed as a standalone Python script or within a Jupyter Notebook.
Once the code is executed, the system will return the top 3 listings personalized for the buyer.
