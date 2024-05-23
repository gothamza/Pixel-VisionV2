# 🚀 health care chatbot in criticale cases
We are building a chat bot in medical care, but we add a system prompt so that it only answers the user in first aid when he uses an image to chat with it, and we use the base model Lava Med when he wants to share his information about health care in general. we were aiming to add stable diffusion model to show how to do eatche step to take care of the injery, but the results was bad, and tavily API to provide resources and nllb to translate, but we didnt manage to implement that in time.

we add an option for the user to save the chat localy as csv 
HELPs :

This project demonstrates how to run and manage models locally using [Ollama](https://ollama.com/) by creating an interactive UI with [Streamlit](https://streamlit.io).

The app has a page for running chat-based models and also one for nultimodal models (llava-med-v1.6) for vision.

## before started make sure to have this model in your ollama 

  **rohithbojja/llava-med-v1.6:latest**

- use the system page to dowload it in case 

- or use this cmd ollama run rohithbojja/llava-med-v1.6:latest


## Features

- **Interactive UI**: Utilize Streamlit to create a user-friendly interface.
- **Local Model Execution**: Run your Ollama models locally without the need for external APIs.
- **Real-time Responses**: Get real-time responses from your models directly in the UI.

## Installation

Before running the app, ensure you have Python installed on your machine. Then, clone this repository and install the required packages using pip:

```bash
git clone https://github.com/gothamza/Pixel-VisionV2.git
```

```bash
cd Pixel-Vision
```

```bash
pip install -r requirements.txt
```
```bash
ollama pull rohithbojja/llava-med-v1.6:latest
or
ollama run rohithbojja/llava-med-v1.6:latest
```
## Usage

To start the app, run the following command in your terminal:

```bash
streamlit run 01_💬_Chat_Demo.py
```

Navigate to the URL provided by Streamlit in your browser to interact with the app.

**NB: Make sure you have downloaded [Ollama](https://ollama.com/) to your system.**



## Acknowledgments

👏 Kudos to the [Ollama](https://ollama.com/) team for their efforts in making open-source models more accessible!


##This is the link for the presentation 
the demo also in the presentation

https://www.canva.com/design/DAGFnNjTs78/Ntkk7AJddiaiGzvUZIkjMQ/edit?utm_content=DAGFnNjTs78&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton