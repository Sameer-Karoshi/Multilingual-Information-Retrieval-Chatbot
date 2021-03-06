# **Mulilingual Information Retrieval Chabot**
Today, we live in an information, communication, and technology era. Information and data have become a major part of our life. Studies have shown that people are spending over 8 hours on electronic gadgets that are a world full of information in themselves. But this available information is scattered all over the internet and if a user wants an accurate solution for his quibble, the user needs to read a lot of articles and blogs which is tedious and time consuming. Also, this information is generally available only in English language making it difficult to understand for the non-English speakers. Keeping this in mind, we have developed a multilingual chatbot that will give a response to any query in a fraction of seconds. The response will be given in the same language the query was searched or we can also select the language from the pool. Natural Language Processing (NLP) is used for language-related processing. We have used TF-IDF for document retrieval, BM-25 model for passage extraction and spaCy model for answer extraction. Finally, we have developed the proposed system as an android application as well as a website to make it device independent.

From app/website user will enter query that query will go to the server that is google cloud. We hosted our website on google cloud app engine and all python scripts are on google cloud's compute engine. Communication between app/website to google cloud is done by using flask api. All back-end processes are understood by seeing the flowchart mentioned below and finally, we can see the answer on app/website.

### **Note**
In android folder android application's source code is there and in website folder website's source code is there and similarly in server folder python scipts are there. 
 

## **Flowchart**
![alt text](https://github.com/Sameer-Karoshi/Multilingual-Information-Retrieval-Chatbot/blob/master/Flowchart.JPG)

## **Android Application Demo**

![alt text](https://github.com/Sameer-Karoshi/Multilingual-Information-Retrieval-Chatbot/blob/master/android-demo.gif)

## **Website Demo**

![alt text](https://github.com/Sameer-Karoshi/Multilingual-Information-Retrieval-Chatbot/blob/master/website-demo.gif)
