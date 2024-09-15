# GailAssist: Retrieval Augmented generation (RAG) chatbot using OpenAI GPT Model, Langchain, ChromaDB, and Gradio

**GailAssist** supports both PDFs and Docs. 

**The chatbot offers versatile usage through three different methods:**
1. **Offline Documents**: Engage with documents that you've pre-processed and vectorized. These documents can be seamlessly integrated into your chat sessions.
2. **Real-time Uploads:** Easily upload documents during your chat sessions, allowing the chatbot to process and respond to the content on-the-fly.
3. **Summarization Requests:** Request the chatbot to provide a comprehensive summary of an entire PDF or document in a single interaction, streamlining information retrieval.

To employ any of these methods, simply configure the appropriate settings in the "RAG with" dropdown menu within the chatbot interface. Tailor your interactions with documents to suit your preferences and needs efficiently.

* The project provides guidance on configuring various settings, such as adjusting the GPT model's temperature for optimal performance.
* The user interface is crafted with gradio, ensuring an intuitive and user-friendly experience.
* The model incorporates memory, retaining user Q&As for an enhanced and personalized user experience.
* For each response, you can access the retrieved content along with the option to view the corresponding PDF. 

## GailAssist User Interface




Extra read:
- [GPT model](https://platform.openai.com/docs/models/overview) 
- [Gradio](https://www.gradio.app/guides/quickstart)
- [Langchain](https://python.langchain.com/docs/get_started/quickstart)
- [ChromaDB](https://www.trychroma.com/)
