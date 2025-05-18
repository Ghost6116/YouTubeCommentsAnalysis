YouTubeCommentsAnalysis
A Python project to scrape YouTube video comments and analyze their sentiment using NLP techniques.
Prerequisites

Python 3.6+
YouTube Data API v3 Key
pip (Python package manager)

Installation

Clone the Repository
git clone https://github.com/Ghost6116/YouTubeCommentsAnalysis.git
cd YouTubeCommentsAnalysis


Set Up Virtual Environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate


Install Dependencies
pip install -r requirements.txt

Note: Common dependencies may include google-api-python-client, nltk, vaderSentiment, pandas, and plotly.

Configure API Key

Create a client_secrets.json file or set your YouTube Data API key in the environment:export GOOGLE_API_KEY='your-api-key'


Alternatively, update the API key in the main script (e.g., app.py or main.py).



Usage

Run the AnalysisAnalyze comments for a YouTube video by providing its URL or ID:
python main.py --video_url "https://www.youtube.com/watch?v=VIDEO_ID"

Note: Replace main.py with the actual script name and adjust arguments as per the repository.

View Results

Sentiment analysis results (positive, negative, neutral) are saved as CSV files or displayed via visualizations (e.g., pie charts) in the output/ directory.



Example
python app.py --video_url "https://www.youtube.com/watch?v=dQw4w9WgXcQ" --output output/results.csv

Dependencies

google-api-python-client: For YouTube Data API access
nltk, vaderSentiment: For sentiment analysis
pandas, plotly: For data processing and visualization

Notes

Ensure your API key has sufficient quota for comment scraping.
Check the repository for specific script names or additional configuration steps.
For advanced features, refer to the project’s documentation or scripts.

