Ragmine - CLI RAG-Based Agent Framework

Welcome to Ragmine, a powerful CLI-based agent framework preconfigured with Retrieval-Augmented Generation (RAG) capabilities. Ragmine streamlines document analysis and knowledge retrieval through easy integration with databases, models, and prompts. 

## Features

- Database Flexibility**: Connect to external databases like MongoDB or use the inbuilt ChromaDB.
- Document Parsing**: Accepts documents in PDF format for semantic processing.
- Model Selection**: Choose from multiple supported LLMs, including OpenAI's models, LLaMA, and more.
- Interactive Prompts**: Ask questions based on your documents and get precise, context-aware answers.
- Effortless CLI Workflow**: Seamlessly guide users through database selection, document input, model configuration, and prompt interaction.

---

Getting Started

### Prerequisites

Ensure you have the following installed on your system:

1. Python 3.8+
2. pip (Python package manager)
3. git (for cloning the repository)
4. Necessary Python dependencies listed in `requirements.txt`.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ragmine.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ragmine
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Install Ragmine CLI:
   ```bash
   python setup.py install
   ```

---

## Usage

Once installed, use the Ragmine CLI as follows:

1. Run the CLI:
   ```bash
   ragmine
   ```
2. Follow the interactive steps**:
   - Select the database:
     - External (e.g., MongoDB)
     - Inbuilt (ChromaDB)
   - Provide the path to the document in PDF format.
   - Select the desired language model (e.g., OpenAI, LLaMA).
   - Enter your prompts to query the document.

3. Receive contextual answers: The RAG-based agent will process your query and return precise responses.

---

## Example Workflow

```bash
$ ragmine
Welcome to Ragmine - Your CLI-based RAG Agent Framework!

Step 1: Select the database you want to use:
1. MongoDB (External)
2. ChromaDB (Inbuilt)
> 2

Step 2: Provide the path to your document (PDF):
> /path/to/document.pdf

Step 3: Choose the model:
1. OpenAI
2. LLaMA
> 1

Step 4: Enter your prompt:
> What are the key findings in this document?

Processing...

Answer:
The document highlights key findings in the field of AI, including advancements in RAG techniques.
```

---

## Configuration

### Environment Variables

To connect to external databases or API keys, set the following environment variables:

- `MONGODB_URI`: Connection string for MongoDB.
- `OPENAI_API_KEY`: Your OpenAI API key.
- `LLAMA_MODEL_PATH`: Path to the LLaMA model weights.

---

## Contribution

We welcome contributions to improve Ragmine! Follow these steps:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For any queries or support, please reach out to us at **support@ragmine.com**.

Happy querying with Ragmine! 🚀
