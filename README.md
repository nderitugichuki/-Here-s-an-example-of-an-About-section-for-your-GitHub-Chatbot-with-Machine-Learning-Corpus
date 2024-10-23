# Chatbot with Machine Learning Corpus

This chatbot project leverages Natural Language Processing (NLP) techniques and a machine learning corpus to simulate human-like conversations. The chatbot processes user input, compares it to a custom knowledge base (corpus), and responds with the most relevant sentence using TF-IDF vectorization and cosine similarity.

### Features:
- **Machine Learning Corpus Integration**: The chatbot is tuned to respond using a custom machine learning corpus that allows it to generate more specific and contextually relevant responses.
- **Text Preprocessing**: The input is tokenized, normalized (lowercased, punctuation removed), and lemmatized for consistency in responses.
- **TF-IDF & Cosine Similarity**: The chatbot uses TF-IDF (Term Frequency-Inverse Document Frequency) to vectorize the user input and the corpus, and cosine similarity to identify the most relevant response from the corpus.
- **Greeting Detection**: The bot recognizes and responds to common greetings.
- **Polite Exit**: The user can type 'Bye' to end the conversation or 'Thanks' to receive a polite acknowledgment from the bot.
  
### Project Goals:
- **Interactive Chatbot**: Provide an engaging, intelligent conversation experience using a custom-trained chatbot with a machine learning corpus.
- **NLP-Based Responses**: Utilize NLP techniques to improve the relevance and context of the chatbot's responses.
- **Learning Integration**: Showcase the integration of machine learning and NLP in chatbot applications.

### Technologies Used:
- Python
- Natural Language Toolkit (NLTK)
- Scikit-learn (for TF-IDF vectorization and cosine similarity)
- Custom Machine Learning Corpus

### How It Works:
1. The user initiates the conversation, and the chatbot responds based on input patterns and pre-trained data from the machine learning corpus.
2. The chatbot tokenizes and processes the input to match it with the most similar sentence in the corpus.
3. The chatbot generates relevant responses using TF-IDF and cosine similarity to find contextually accurate answers.

