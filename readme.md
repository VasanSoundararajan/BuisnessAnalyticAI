# Business Intelligence Assistant

A fully functional AI-powered Business Intelligence Assistant built using Python, LangChain, and Gradio. This project provides an interactive web interface for loading business data, generating statistical summaries, answering business questions, and visualizing data trends.

## Features

- **Data Loading**: Upload CSV files to load business data.
- **Statistical Summaries**: Automatically generate concise statistical summaries of the data.
- **Question Answering**: Use AI to answer business-related questions based on the loaded data.
- **Data Visualization**: Generate visualizations for sales trends and product performance.
- **User-Friendly Interface**: Built with Gradio for an intuitive user experience.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- pip

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/business-intelligence-assistant.git
    cd business-intelligence-assistant
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

### Running the Assistant

1. Run the Gradio application:

    ```bash
    python main.py
    ```

2. Open your web browser and navigate to the URL provided by Gradio (usually `http://localhost:7860`).

### Using the Assistant

1. **Data Setup**:
    - Upload a CSV file containing your business data.
    - Click "Load Data" to load and preview the data.
    - Click "Initialize System" to prepare the AI model and knowledge base.

2. **Ask Questions**:
    - Enter a business question in the "Your business question" box.
    - Click "Ask" to get an AI-generated answer.

3. **Visualizations**:
    - Select a visualization type from the dropdown menu.
    - Click "Generate Plot" to visualize the data trends.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [LangChain](https://github.com/langchain-ai/langchain) for providing the necessary tools for embeddings and LLMs.
- [Gradio](https://github.com/gradio-app/gradio) for creating the interactive web interface.
- [Hugging Face Transformers](https://github.com/huggingface/transformers) for the pre-trained models and tokenizers.

## Contact

For any questions or feedback, please contact [vasansoundararajan.21@gmail.com](mailto:vasansoundararajan.21@gmail.com).
