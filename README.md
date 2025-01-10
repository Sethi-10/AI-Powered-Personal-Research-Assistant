# AI-Powered Personal Research Assistant

This project is a highly practical and advanced implementation of an AI-Powered Personal Research Assistant. It showcases cutting-edge capabilities in Retrieval-Augmented Generation (RAG), Large Language Models (LLMs), and LangChain. With an enhanced feature set and a user-friendly interface, this assistant is designed to streamline your research process effectively.

## Table of Contents

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
<img width="1440" alt="Screenshot 2025-01-08 at 3 42 02 PM" src="https://github.com/user-attachments/assets/c0dbd87e-c3e8-46a3-897e-0bc98d700154" />

<img width="1440" alt="Screenshot 2025-01-08 at 3 40 23 PM" src="https://github.com/user-attachments/assets/6b754894-f296-4f20-a3eb-f575e3fdc00f" />

<img width="1440" alt="Screenshot 2025-01-08 at 3 40 25 PM" src="https://github.com/user-attachments/assets/46a5c1f6-977c-4430-8735-5ff356b7a241" />

<img width="1440" alt="Screenshot 2025-01-08 at 2 56 52 PM" src="https://github.com/user-attachments/assets/84ee07dd-4d97-40ab-b70d-e37797206623" />

<img width="1440" alt="Screenshot 1" src="https://github.com/user-attachments/assets/8bccc75c-dbc6-40c9-b8a0-5a5e027c02ac" />

<img width="1440" alt="Screenshot 2" src="https://github.com/user-attachments/assets/e6929b11-0d9e-4014-81b1-601331933468" />

<img width="1440" alt="Screenshot 3" src="https://github.com/user-attachments/assets/b6c9ae67-8010-47c0-9aa8-7aabd772ae37" />


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
