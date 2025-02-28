# Integrating Large Language Model with GiziSight
Try Out The Demo Here : [![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://gizisight-with-llm.streamlit.app/)

# Project Description
This project is a follow-up project of GiziSight by integrating LLM and maintaining the main core of GiziSight which is Computer Vision model. In this project, I changed the previous computer vision model [EfficientNetV2S](https://arxiv.org/abs/2104.00298) to [Convolutional Vision Transformer](https://arxiv.org/abs/2103.15808). I did Fine Tuning of all layers in it using AdamW optimizer and two LRDecay (LinearLR for warmup LR & CosineAnnealingLR for decreasing LR) with 3 epoch. For LLM integration, here I use Qwen 2.5 32B via [Groq API](https://console.groq.com/keys) and GPT-4o mini via [Open AI API](https://platform.openai.com/api-keys).
