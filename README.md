
# oaqjp-final-project-emb-ai

Final Project

IBM Skills Network final project: Emotion Detection using the Watson NLP EmotionPredict service and a Flask web application.

Features
Detects anger, disgust, fear, joy, and sadness.
Identifies the dominant emotion.
Provides a browser interface using Flask.
Handles empty input and API failures.
Run in Skills Network Theia Lab
Install dependencies:

python3 -m pip install requests flask pylint pytest
Start the application:

python3 server.py
Open the Theia preview for port 5000 and enter a sentence to analyze.

Run tests:

python3 -m pytest -q
Run static analysis:

python3 -m pylint server.py
