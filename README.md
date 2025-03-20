# PDF-summarization

This implementation provides a complete solution for AI-driven text extraction and summarization with the following features:

Custom Text Processing System:

Uses Hugging Face transformers (BART and DistilBERT) as the foundation
Handles both summarization and information extraction
Processes long documents by intelligently chunking and combining results


API Endpoints:

/analyze: Main endpoint for text processing (summarization and extraction)
/fine-tune: Endpoint for customizing the model on domain-specific data
/health: Simple health check endpoint


Advanced Capabilities:

Fine-tuning functionality to adapt the model to your specific domain
Handles long documents by intelligently splitting and recombining
Question-answering extraction for targeted information retrieval


Production-Ready Features:

Proper error handling and logging
GPU acceleration when available
Configurable parameters for summary length and extraction



To use this system:

Install the required packages: pip install torch transformers flask nltk datasets
Run the application: python app.py
Send requests to the API endpoints with your text data
