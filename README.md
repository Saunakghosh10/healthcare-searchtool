# PubMed Healthcare Chatbot. LLM Augmented Q&A over PubMed Search Engine.

![hc](https://github.com/Saunakghosh10/healthcare-searchtool/assets/76943154/7956586a-51fa-4e1d-9fe9-572e1a4a18b3)

# PubMed Healthcare Chatbot

PubMed Healthcare Chatbot is an AI-powered assistant designed to provide healthcare-related information by integrating PubMed search capabilities with a Large Language Model (LLM). This chatbot leverages advanced natural language processing to understand user queries and retrieves relevant articles from PubMed to generate accurate and informative responses.

## Features

- **Natural Language Processing**: Understands and processes natural language queries.
- **PubMed Integration**: Searches the PubMed database for relevant articles and information.
- **LLM Augmentation**: Uses advanced language models to generate coherent and informative responses.
- **User-Friendly Interface**: Seamless interaction through a web interface powered by Gradio.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get started with PubMed Healthcare Chatbot, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/saunak10/healthcare-searchtool.git
    cd healthcare-searchtool
    ```

2. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up API keys**:
    - Obtain an API key from HuggingFace.
    - Create a `.env` file in the root directory and add your HuggingFace API key:
      ```
      HUGGINGFACE_API_KEY=your_huggingface_api_key_here
      ```

4. **Run the application**:
    ```bash
    python app.py
    ```

## Usage

Once the application is running, you can interact with the chatbot through a web interface powered by Gradio.

### Example Commands

- **Ask a healthcare question**:
    ```
    How are mRNA vaccines being used for cancer treatment?
    ```

- **Request specific article information**:
    ```
    Suggest me some Case Studies related to Pneumonia.
    ```

## Configuration

The configuration is managed through environment variables and a `config.json` file. Ensure you have set up the `.env` file with your HuggingFace API key.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. **Fork the repository**.
2. **Create a new branch**:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. **Make your changes**.
4. **Commit your changes**:
    ```bash
    git commit -m "Add feature: your feature name"
    ```
5. **Push to the branch**:
    ```bash
    git push origin feature/your-feature-name
    ```
6. **Create a pull request**.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Feel free to customize this template according to your project's specifics and requirements.
