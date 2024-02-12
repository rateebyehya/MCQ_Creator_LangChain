# MCQ CREATOR WITH LANGCHAIN

A QUIZ MCQ CREATOR Application that leverages Langchain's Data Connection Module to generate multiple-choice questions from a PDF with correct answers!

🚀 TRANSFORMING DATA INTO KNOWLEDGE WITH LANGCHAIN 🚀

🌐 In my sixth project on Langchain and Hugging Face with my mentor SHARATH RAJU, I delve into LANGCHAIN'S DATA CONNECTION MODULE which enables users to enhance the LLM's understanding by providing it with additional information beyond what it has been trained on, from EXTERNAL SOURCES like PDF!

🌟 A QUIZ MCQ CREATOR Application that leverages Langchain's Data Connection Module to generate multiple-choice questions from a PDF with correct answers! 🎉

💡 Here's a glimpse into the technical wizardry behind the scenes:

----> DOCUMENT LOADERS: Langchain's Document Loaders import PDF files into our application, providing the foundation for further analysis. The PDF we used was a 2-page PDF from LangChain's DATA CONNECTION MODULE found here: 

https://python.langchain.com/docs/modules/data_connection/

----> TEXT SPLITTING: Employing Langchain's Text Splitting module, we break down the loaded document into manageable chunks while maintaining contextual coherence, ensuring the extracted information remains meaningful and informative.

----> TEXT EMBEDDINGS: Utilizing Hugging Face's SENTENCE TRANSFORMER EMBEDDINGS, we transform textual content into numerical vectors, laying the groundwork for efficient processing and retrieval.

----> VECTOR STORES: With PINECONE'S vector store, we store the generated embeddings alongside the original documents, enabling fast and effective retrieval of relevant information based on user queries.

----> RETRIEVAL: Leveraging HuggingFace's BigScience BLOOM model, we retrieve answers to user questions from the vector store, providing accurate and contextually relevant responses.

----> OUTPUT PARSING: Through LANGCHAIN'S OUTPUT PARSERS, we structure the output into a user-friendly format, ensuring a seamless interaction experience for users.


WITH LANGCHAIN, you can NOW RETRIEVE ANSWERS FROM YOUR OWN PDF DOCUMENTS!!! PRETTY COOL HUH?
