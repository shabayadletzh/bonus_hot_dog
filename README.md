# Hot Dog not Hot Dog Assignment

## Adilet Shabay

In this project, we built and deployed a computer vision web application using Streamlit to handle the user interface and ngrok to tunnel the local server (Google Colab) to the public internet. The previous deployment method (localtunnel) caused WebSocket errors that broke the file uploader, so we migrated to ngrok for a stable connection. To address the "Jinyang problem"—where the original app was a useless binary classifier that could only detect "Hot Dog" or "Not Hot Dog"—we implemented a multi-class image classification model using the Hugging Face transformers library. By loading the nateraw/food model (trained on the Food-101 dataset), the application can now accurately identify and label 101 different specific food categories, making the tool genuinely useful for the user.

** Note: ** please be advised that your computer might have troubles running streamlit app because browser or antivirus programs can be block it as "untrusted website". The code is running and the app works, but streamlit might cause some issues to run.
