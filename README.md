# AI-Powered Personal Research Assistant

This project is a highly practical and advanced implementation of an AI-Powered Personal Research Assistant. It showcases cutting-edge capabilities in Retrieval-Augmented Generation (RAG), Large Language Models (LLMs), and LangChain. With an enhanced feature set and a user-friendly interface, this assistant is designed to streamline your research process effectively.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Snapshots](#snapshots)
  - [GUI-Interface](#gui-interface)
- [Technologies Used](#technologies-used)
- [Future Enhancements](#future-enhancements)
- [Acknowledgements](#acknowledgements)

## Features

### 1. **LangChain Integration**
   - Leverages LangChain using HuggingFaceHub to provide insightful responses based on article summaries.
   - Supports interaction with state-of-the-art language models for enhanced AI-driven analysis.

### 2. **Graphical User Interface (GUI)**
   - A simple, intuitive GUI built with Tkinter.
   - Allows users to input queries and retrieve insights with ease.

### 3. **Error Handling**
   - Robust try-except blocks ensure graceful handling of potential runtime errors.
   - Provides meaningful error messages for debugging and user guidance.

### 4. **Caching System**
   - Implements a file-based caching system to store and retrieve previously fetched results.
   - Optimizes performance and reduces redundant API calls.

### 5. **Advanced NLP Features**
   - **Named Entity Recognition (NER)**: Utilizes spaCy to extract and analyze named entities from fetched articles.
   - **Topic Modeling**: Gensim's LDA model identifies and organizes topics from large datasets for better understanding.
   - **Summarization**

### 6. **Modular Design**
   - Restructured into classes and modules for improved organization and maintainability.
   - Promotes reusability and extensibility of the codebase.

## Installation

1. Clone this repository:
   ```bash
   git clone ""
   cd ai-research-assistant
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the required spaCy model:
   ```bash
   python -m spacy download en_core_web_sm
   ```

4. Set up your HuggingFace API token:
   - Create an account on [HuggingFace](https://huggingface.co/).
   - Generate a free API token from your account settings.
   - Add the token to your environment variables:
     ```python
     os.environ["HUGGINGFACEHUB_API_TOKEN"] = "your_huggingface_token_here"
     ```

## Usage

1. Run the application:
   ```bash
   python application.py
   ```

2. Use the GUI to:
   - Enter your research query.
   - Retrieve article summaries and insights.
   - Explore NLP features like Named Entity Recognition and Topic Modeling.

## Snapshots

### GUI-Interface
![alt text](file:///c%3A/Users/aryan/Downloads/Screenshot%202025-01-08%20at%203.42.02%E2%80%AFPM.png)
![alt text](file:///c%3A/Users/aryan/Downloads/Screenshot%202025-01-08%20at%203.40.23%E2%80%AFPM.png)
![alt text](file:///c%3A/Users/aryan/Downloads/Screenshot%202025-01-08%20at%203.40.25%E2%80%AFPM.png)
![alt text](file:///c%3A/Users/aryan/Downloads/Screenshot%202025-01-08%20at%202.56.52%E2%80%AFPM.png)
![alt text](file:///c%3A/Users/aryan/Downloads/Screenshot%202025-01-08%20at%202.58.03%E2%80%AFPM.png)
![alt text](file:///c%3A/Users/aryan/Downloads/Screenshot%202025-01-08%20at%202.54.36%E2%80%AFPM.png)
![alt text](file:///c%3A/Users/aryan/Downloads/Screenshot%202025-01-08%20at%202.54.57%E2%80%AFPM.png)

## Technologies Used

- **LangChain**: For interaction with LLMs via HuggingFaceHub.
- **spaCy**: For Named Entity Recognition (NER).
- **Gensim**: For topic modeling using LDA.
- **Tkinter**: For building the GUI.
- **Python**: For implementation and orchestration of the project components.

## Future Enhancements

- Adding support for more advanced visualization tools (e.g., Matplotlib, Plotly).
- Extending the caching system to support cloud storage.
- Incorporating real-time collaboration features.


## Acknowledgments

- [HuggingFace](https://huggingface.co/) for providing powerful APIs for LLMs.
- [spaCy](https://spacy.io/) for NLP tools.
- [Gensim](https://radimrehurek.com/gensim/) for topic modeling.
- Open-source contributors for their valuable tools and resources.