# CallBotX: AI-Powered Voice Agents for E-Commerce Support

## 📝 Code Explanation
This project uses Jupyter notebooks and Python scripts to build a Retrieval-Augmented Generation (RAG) chatbot for e-commerce support. The main notebook (`RAG_Chatbot.ipynb`) demonstrates:
- Loading product data (PDFs, docs)
- Splitting and embedding documents for semantic search
- Using Langchain and Groq Llama3 for question answering
- Building a retriever and prompt template for context-aware responses
- Streaming answers and converting them to voice (gTTS)

### Example Workflow
1. Load product data (e.g., iPhone specs PDF)
2. Split text into chunks and embed for retrieval
3. Use Langchain retriever to find relevant context
4. Pass context and user question to Llama3 model
5. Return answer and optionally convert to speech

## Usage
Run `RAG_Chatbot.ipynb` in Jupyter. Follow the code cells to:
- Set up API keys and environment
- Load and process product documents
- Ask questions and get AI-powered answers
- Convert answers to voice using gTTS

This repo is ideal for building custom voice/text AI agents for product support.

CallBotX is a platform that leverages Retrieval-Augmented Generation (RAG) techniques and natural voice interaction to answer user queries about specific products (initially focusing on iPhones 8–16). It enables companies to upload their product information and, within minutes, deploy a custom AI assistant capable of handling real customer conversations in both text and voice formats.

## Features

- **AI Voice & Text Agents:** Instantly create AI agents that can interact with customers using natural language via voice and chat.
- **Retrieval-Augmented Generation (RAG):** Uses advanced retrieval techniques to provide accurate, up-to-date answers based on product documentation and FAQs.
- **Rapid Onboarding:** Companies can upload their product information and quickly deploy an AI-powered assistant.
- **Multimodal Support:** Handles both voice and text interactions for seamless customer support.
- **Customizable:** Easily adapt the assistant to support new products and business requirements.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook (for exploring or running code interactively)
- Required Python packages (see your environment or requirements)

### Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Muhammad-Muzammil-Shah/CallBotX-AI-Powered-Voice-Agents-for-E-Commerce-Support.git
   cd CallBotX-AI-Powered-Voice-Agents-for-E-Commerce-Support
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
   *(If `requirements.txt` is not present, install dependencies as listed in the notebooks.)*

3. **Upload Product Information**
   - Prepare product documentation or data as specified in the instructions (see notebooks or documentation).
   - Use the provided interface or scripts to upload product information.

4. **Run the Platform**
   - Launch the main application (instructions will be in the main notebook or script).
   - Follow prompts to set up your AI agent.

## Usage

- Interact with the AI agent via the provided web or voice interface.
- Test with sample product queries (e.g., "What are the features of iPhone 12?").
- Adapt and extend to new products by uploading additional information.

## Repository Structure

- **Jupyter Notebooks:** Core logic, RAG implementation, and examples.
- **Scripts & Modules:** Backend for voice/text interaction and data processing.
- **Documentation:** Guides for onboarding, integration, and customization.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project does not currently specify a license. Please contact the repository owner for usage terms.

## Contact

- **Author:** [Muhammad-Muzammil-Shah](https://github.com/Muhammad-Muzammil-Shah)
- For questions or support, please open an issue on the [GitHub repository](https://github.com/Muhammad-Muzammil-Shah/CallBotX-AI-Powered-Voice-Agents-for-E-Commerce-Support).

---
*Empowering e-commerce with intelligent, conversational support.*
