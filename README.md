# Product Review Sentiment Analysis + Reasoning

An interactive Gradio-based web app that classifies customer reviews into Positive, Neutral, or Negative sentiment, explains the reasoning behind the classification, and optionally rephrases the feedback in a neutral or brand-friendly tone.  
Designed for e-commerce teams to quickly understand customer emotions and prepare professional responses.

---

##  Features

- **Sentiment Classification**: Detect Positive, Neutral, or Negative tone in reviews
- **AI-Powered Explanations**: GPT generates concise reasoning for the sentiment
- **Review Rephrasing**: Convert emotional or harsh reviews into neutral or brand-friendly language
- **Export & Copy**:  
  - Export all analyses to JSON  
  - Copy results directly to clipboard
- **Fallback**: If the transformer model is unavailable, falls back to `TextBlob`


