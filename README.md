# Movie Recommendation System

## Project Overview

The Movie Recommendation System is a web application that suggests personalized movie recommendations based on a user's favorite genres and top 3 favorite movies. The application uses OpenAI's GPT-4 model to generate recommendations and OMDb API to fetch movie posters.

## Features

- **Personalized Recommendations:** Users can select their favorite movie genres and list their top 3 favorite movies. Based on this information, the application generates personalized movie recommendations.
- **Movie Posters:** The application displays posters for the recommended movies using the OMDb API.
- **Feedback Mechanism:** After receiving recommendations, users can provide feedback on whether they liked the recommendations. If the user didn't like the recommendations, the application generates new suggestions based on the same preferences.

## Technologies Used

- **Python**
- **Streamlit:** For creating the web application interface.
- **OpenAI GPT-4:** For generating movie recommendations.
- **OMDb API:** For retrieving movie posters.

## Installation and Setup

### Prerequisites

Before running the application, ensure that you have the following installed:

- Python 3.7 or higher
- Pip (Python package installer)

### Step-by-Step Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/movie-recommendation-system.git
   cd movie-recommendation-system

### Set Up Your API Keys:

- **OpenAI API Key:** You need to obtain an API key from OpenAI.
- **OMDb API Key:** You can get a free API key by signing up on the OMDb website.
Once you have your API keys, replace 'YOUR_OPENAI_API_KEY' and 'YOUR_OMDB_API_KEY' in the app.py file with your actual keys.


### Usage
- **1.	Select Genres:** Choose your favorite movie genres from the provided list.
- **2.	Enter Favorite Movies:** Input your top 3 favorite movies.
- **3.	Get Recommendations:** Click the "Get Recommendations" button to receive personalized movie suggestions.
- **4.	View Posters:** Posters of the recommended movies will be displayed below the recommendations.
- **5.	Provide Feedback:** After reviewing the recommendations, you can indicate whether you liked them or not. If you didn't like them, new recommendations will be generated based on your initial preferences.

