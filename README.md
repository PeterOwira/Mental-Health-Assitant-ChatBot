# Mental-Health-Assitant-ChatBot
Mental Health Chatbot using Llama 2 and Sentiment Analysis Integration

This project aims to create an Emotionally Intelligent Chatbot for Mental Health support. It combines two key components: an `Emotion Classifier Model` created by [SamLowe](https://huggingface.co/SamLowe/roberta-base-go_emotions) and the `Llama language model` created by [NousResearch](https://huggingface.co/NousResearch/Llama-2-7b-chat-hf). The emotion classifier analyzes user input to determine their emotional state, providing detailed scores for emotions like sadness, joy, and anger. This emotional context is then integrated into prompts for `Llama 2`, enabling it to generate responses that are both contextually relevant and emotionally appropriate.
The chatbot is designed to detect when users are feeling down and provide supportive, empathetic responses. It acknowledges the user's emotional state, addresses their concerns, and offers encouragement. This system aims to provide a supportive presence for users, especially during times of emotional distress.

Key features include:
1.   Real-time emotion analysis of user input
2.   Context-aware response generation using Llama 2
3.   Tailored support based on detected emotional states
4.   Conversational communication style

While not a replacement for professional mental health care, this chatbot serves as a supplementary tool for emotional support and a potential first point of contact for those seeking help. The project shows the importance of responsible AI implementation in mental health applications, including appropriate disclaimers and safeguards.
