#Overview

    This project is a PDF analysis tool designed to extract text, images, and links from uploaded PDF files. The workflow includes a character text splitter using Langchain, OpenAI 
  embeddings and FAISS operations to enhance search capabilities. Users can input prompts, and the system generates relevant outputs based on similarity search.

#Key Features
  #PDF Content Extraction: 
      Extracts text, images, and links from PDF files, providing a comprehensive overview of the document's content.

  #Character Text Splitter (Langchain): 
      Implements Langchain for character-level text splitting, enhancing the granularity of text analysis.

  #OpenAI Embeddings: 
      Leverages OpenAI embeddings to understand and represent the semantic meaning of the extracted text, enabling more nuanced analysis.

  #FAISS Operations: 
      Utilizes FAISS for fast and efficient similarity searches, allowing users to find relevant information based on their queries.

  #User Interaction: 
      Facilitates user interaction by accepting prompts, enabling customized searches and output generation.

##Dependencies
PyPDF2: For PDF file handling and text extraction.
Langchain: Character text splitter for language processing.
OpenAI: Utilized for embeddings and semantic analysis.
