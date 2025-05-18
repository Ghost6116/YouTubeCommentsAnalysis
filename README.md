# YouTubeCommentsAnalysis

Python project to scrape and analyze YouTube video comments' sentiment.

## Setup

1. **Clone Repo**
   ```bash
   git clone https://github.com/Ghost6116/YouTubeCommentsAnalysis.git
   cd YouTubeCommentsAnalysis
   ```

2. **Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set API Key**
   - Add YouTube Data API key to `client_secrets.json` or:
     ```bash
     export GOOGLE_API_KEY='your-api-key'
     ```

## Run

Analyze comments:
```bash
python main.py --video_url "https://www.youtube.com/watch?v=VIDEO_ID"
```

## Output
- Sentiment results (CSV or charts) in `output/`.

## Requirements
- Python 3.6+
- `google-api-python-client`, `nltk`, `vaderSentiment`, `pandas`

*Note*: Check repo for exact script names and setup.
