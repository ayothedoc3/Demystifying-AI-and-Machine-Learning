Demystifying AI and ML - Run Sheet
Audience: mixed technical level
Total length: 60 to 75 minutes

0 - 5 min: Warm open
- Ask: Who writes Python weekly, who is new, who ships to users
- Promise: You will train a model and know how to avoid the top mistakes

5 - 15 min: Mental models that stick
- AI vs ML vs Deep Learning, one slide
- The loop: Data, Features, Model, Metrics, Deploy
- Success metric example: accuracy vs F1, why it matters

15 - 35 min: Live coding 1, Iris classification
- Open 02_classification_iris.ipynb
- Show train test split, baseline logistic regression
- Show accuracy and report, then try RandomForest
- One visual: feature importance bar chart
- Message: simple, strong baseline

35 - 55 min: Live coding 2, Text sentiment
- Open 03_text_sentiment_baseline.ipynb
- Explain bag of words and logistic regression
- Predict on two new sentences from the room

55 - 65 min: Responsible AI in practice
- Bias sources: data, labels, sampling
- Privacy: avoid storing PII without consent
- Human in the loop: review and override

65 - 75 min: Q and A and resources
- Show slides.md short recap
- Share the GitHub style structure you would use in production

Room tech checklist
- HDMI or USB C adapter, power, clicker
- Python 3.10+, virtualenv, Jupyter installed
- No internet fallback ready, data files are local
- Bright theme option in case the projector is dark

Commands
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook

Talking tone
- Use plain words and short sentences
- Define each term once
- Ask one question every 5 minutes to keep the room engaged