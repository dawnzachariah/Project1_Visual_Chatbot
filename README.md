# Project5_Visual_Chatbot  
a 40 class image classifier + an interactive chatbot + a text to speech converter  

**Title**
Visual Chatbot  

**Problem Statement**  
To build a multi-class classifier app which can classify the inputted image of an Indian monument followed by a chatbot which can answer the queries of the user regarding the classified inputted image as speech.  

**Description**  
- Data:  
  - Images of 40 famous monuments of India web scraped from flickr. 
  - Text data for chatbot purpose was web scraped from wikipedia.

- In our app the user can input the monument image to be classified. Then the classifier built using AlexNet identifies and classifies the image.  
- Train accuracy - 92.23%  
- Once the classification is done the user interacts with the chatbot built using AllenNLP if the user wants to know more about the classified monument. The chatbot provides the output with audio.  
- The app is built on Streamlit.    
  - ABOUT option: to know about the app Visual Chatbot  
  - CHATBOT option: chatbot which includes the classifier

