## Donut Model Document Understanding with LangChain and Unstructured Libraries

This project focuses on document understanding using the **Donut Model**, which avoids OCR-based methods for faster and more accurate document parsing. The project utilizes **LangChain** and **Unstructured** libraries to preprocess PDFs, PPTs, and Markdown files, perform document chunking, generate embeddings, and perform similarity-based retrieval.

### Key Libraries and Tools:
- **Unstructured**: For partitioning and processing documents in formats like PDF, PPTX, and Markdown.
- **LangChain**: For document retrieval and conversational question-answering using embeddings.
- **ChromaDB**: Vector database for storing and querying document embeddings.
- **OpenAI (via LangChain)**: Provides AI-driven conversational document interaction.

### Advanced Technology:
- **Donut Model**: A document understanding transformer that eliminates OCR, enabling faster and more efficient document parsing.
- **Conversational Retrieval**: Uses **LangChain**'s `ConversationalRetrievalChain` for answering questions about documents.
- **End-to-End Learning**: The Donut model uses a deep learning approach for document understanding without the need for OCR.

Explore the full project for implementation details and its applications.
