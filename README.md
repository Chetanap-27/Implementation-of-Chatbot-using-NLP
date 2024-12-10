

# NLP-Powered Chatbot

## Overview  
This project is a conversational chatbot that uses Natural Language Processing (NLP) to understand and respond to user inputs. By analyzing text, the chatbot identifies user intents and generates appropriate replies using predefined patterns. The system incorporates libraries like `nltk` for language processing, `scikit-learn` for machine learning, and `streamlit` for creating an engaging and interactive interface.  

---

## Key Features  
- Detects user intents, such as greetings, farewells, and expressions of thanks.  
- Delivers relevant and meaningful responses based on input.  
- Maintains a log of the conversation, accessible for later reference.  
- Built with Python and leverages popular tools to enhance chatbot functionality.  

---

## Tools and Technologies  
- **Python** as the programming language.  
- **NLTK** for text processing and tokenization.  
- **Scikit-learn** for implementing machine learning models.  
- **Streamlit** for building an interactive user interface.  
- **JSON** for managing the chatbot’s intent data.  

---

## Setup Instructions  

### Step 1: Clone the Repository  
Start by cloning the project to your system:  
```bash  
git clone <repository-url>  
cd <repository-directory>  
```  

### Step 2: Set Up a Virtual Environment  
To manage dependencies, it’s recommended to use a virtual environment:  
```bash  
python -m venv venv  
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`  
```  

### Step 3: Install Dependencies  
Use the `requirements.txt` file to install all the necessary libraries:  
```bash  
pip install -r requirements.txt  
```  

### Step 4: Download NLTK Resources  
Download the required data for the `nltk` library:  
```python  
import nltk  
nltk.download('punkt')  
```  

---

## How to Run  
To start the chatbot, execute the following command in your terminal:  
```bash  
streamlit run app.py  
```  
The chatbot interface will open in your browser. You can type messages into the text field and interact with the chatbot in real time.  

---

## Customizing Chatbot Behavior  
The chatbot’s responses and behavior are controlled by an `intents.json` file. This file contains predefined tags, user patterns, and corresponding responses. You can edit this file to introduce new intents or modify existing ones as needed.  

---

## Conversation Log  
The chatbot saves all user interactions in a file named `chat_log.csv`. Users can view their past conversations via an option in the app's sidebar.  

---

## Contribution Guidelines  
Contributions are welcome! If you have ideas to enhance the chatbot or fix any issues, please submit a pull request or report an issue in the repository.  

---

## License  
This project is open-source and distributed under the MIT License. See the [LICENSE](LICENSE) file for full details.  

---

## Acknowledgments  
We extend our gratitude to the following tools and frameworks for enabling this project:  
- **NLTK** for language processing capabilities.  
- **Scikit-learn** for its robust machine learning features.  
- **Streamlit** for building the user-friendly chatbot interface.  

---

Feel free to make further tweaks or additions based on your requirements! Let me know if you need more help.
