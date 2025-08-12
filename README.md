# mental-health-chatbot
Islamic Comfort Chatbot
Task Objective
The goal of this project is to build a supportive mental health chatbot that provides empathetic, Islamic-based comfort for stress, anxiety, and emotional wellness. The chatbot is designed to respond in a gentle and understanding tone, offering reassurance and guidance.

Dataset Used
A custom CSV dataset of Islamic comfort lines was created. Each entry pairs a user prompt, typically expressing emotional distress, with an empathetic response rooted in Islamic teachings and supportive language.

Models Applied
The chatbot is fine-tuned using the Mistral 7B language model, optimized through LoRA (Low-Rank Adaptation) for efficiency. The training process leverages the Hugging Face Transformers library, allowing for lightweight fine-tuning in Colab with GPU acceleration.

Key Results and Findings
The fine-tuned model produces contextually relevant, emotionally supportive, and faith-aligned responses.

Multi-turn interaction is supported, allowing the chatbot to handle extended conversations.

LoRA fine-tuning reduced resource requirements, making the process feasible in a Colab environment.

The resulting model is able to generalize well to unseen user inputs while maintaining a consistent supportive tone.
