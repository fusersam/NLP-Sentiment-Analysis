---
title: Sentimental Analysis  # Replace with your app's title
emoji: 🧠  # Pick an emoji that represents your app
colorFrom: purple  # Starting color for the app gradient
colorTo: pink  # Ending color for the app gradient
sdk: gradio  # Use 'gradio' if you're deploying a Gradio app
sdk_version: "3.50.2"  # Replace with the Gradio version you're using
app_file: app.py  # Entry point of your app (e.g., 'app.py')
pinned: false  # Set to 'true' if you want the space to be pinned
---

# Sentimental Analysis
This app predicts sentiment analysis for provided text input using a pre-trained model.


# Harnessing the Power of Sentiment Analysis: An Exploration with Pre-Trained Models and Gradio App

## Project Description 🧐
This project seeks to fine-tune a pre-trained model to analyse the sentiments on some posts on Twitter that are about the COVID-19 vaccine and classify them into Positive, Neutral and Negative. This refined model will serve the purpose of collecting tweet data related to the epidemic, eliminating the sole reliance on specific keywords like 'covid' or 'coronavirus.' This approach enables researchers and engineers to curate a more inclusive dataset for sentiment analysis.

The potential application of this model lies in its integration into a broader initiative focused on comprehending online sentiments concerning COVID-19. 

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the requirements.txt file. 

```bash
pip install -r requirements.txt
```

## Usage 👍🏾

```powershell

Gradio run app.py


```


## Summary 💬
| Code      | Name        | Published Article |  Deployed App |
|-----------|-------------|:-------------:|------:|
| LP5 | Sentiment Analysis |  [Article to project](https://medium.com/@mdkumassah/harnessing-the-power-of-sentiment-analysis-an-exploration-with-gradio-app-293f22ccb215) | [Deployed App](https://huggingface.co/spaces/QuophyDzifa/Sentiment-Analysis-NLP) |
