# AI-You

## Overview
The AI-YOU is an artificial intelligence program that provides personalized responses based on users' choices, interests, and context. Unlike generic chatbot or virtual assistant products, AI-YOU is designed to understand each user's unique needs and preferences, tailoring its responses accordingly. By offering personalized and contextually relevant responses, AI-YOU aims to deliver a more satisfying and engaging user experience.

## Key Features
* Personalized Responses: AI-YOU analyzes users' choices, interests, and context to provide customized responses that cater to their specific needs.
* Contextual Understanding: The program comprehends the user's current situation, allowing it to generate responses that are relevant to the given context.
* Dynamic Recommendations: AI-YOU can suggest various options based on user preferences, such as recommending different restaurants based on cuisine, budget, and location.
* Step-by-Step Directions: If requested, AI-YOU can provide detailed directions to a recommended restaurant, considering the user's current location and preferred mode of transportation.
* Enhanced User Connection: The personalized responses create a stronger connection with users over time, fostering increased engagement and loyalty.

## How the AI-You Works
AI-YOU utilizes advanced technology to deliver personalized responses. The following steps outline the process:

1. Text Extraction: The program takes a PDF document and converts it into plain text, which is then split into manageable chunks.
2. Text Embedding: Each text chunk is processed to generate an embedding, a numerical representation of the text. The embedding represents different features or attributes of the text in a multi-dimensional Euclidean space.
3. Vector Store Creation: AI-YOU uses Pinecone, a vector database service, to store the generated embeddings as separate vectors. The vectors allow for efficient similarity calculations between different pieces of text.
4. User Interaction: When a user asks a question, the program sends it to the GPT 3.5 language model for processing.
5. Embedding Comparison: AI-YOU creates an embedding for the user's question and compares it to the stored embeddings in the vector store to identify similar texts.
6. Document Retrieval: Based on the similarity calculations, AI-YOU retrieves relevant documents and the user's question.
7. Response Generation: Using the retrieved information, AI-YOU generates a personalized response tailored to the user's question and context.

## Repository Credits
This AI-YOU implementation is built upon the code provided by MayoEar on GitHub. The repository includes a visual guide that explains the workings of AI-YOU. It describes the process of converting PDF documents to text, generating embeddings, creating the vector store using Pinecone, and utilizing GPT 3.5 for language processing.

## Project Showcase: 
![ai_you](https://github.com/TejasDeepLearning/AI-You/blob/main/ai_you.png)
![ai_you_1](https://github.com/TejasDeepLearning/AI-You/blob/main/aiyou_1.png)
![ai_you_2](https://github.com/TejasDeepLearning/AI-You/blob/main/aiyou_2.png)
