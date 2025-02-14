🚀 RAG Evaluation Project
🌟 Overview
This project dives into the exciting world of Retrieval-Augmented Generation (RAG)! 🧠✨ Specifically, we built and evaluated a RAG-powered chatbot designed to answer questions about the Machine Learning School website. The goal? To create a robust knowledge base and generate a test set to assess the chatbot's performance. 🎯

🧠 Key Learnings
1. Environment Setup 🛠️
Used dotenv to securely manage environment variables (like API keys 🔑) and keep sensitive information safe.

Set up the OpenAI API for generating embeddings and responses, making the chatbot smarter and more responsive. 🤖

2. Web Scraping & Document Processing 🕸️
Built a web scraper using WebBaseLoader from the langchain_community library to extract content from the Machine Learning School website. 🖥️

Used RecursiveCharacterTextSplitter to break down the scraped content into bite-sized chunks for easier processing. 📄➡️📦

3. Vector Store Creation 🗄️
Created a vector store using DocArrayInMemorySearch to store processed documents and their embeddings. 🧩

Leveraged OpenAIEmbeddings to convert text into vector representations, making retrieval lightning-fast during question answering. ⚡

4. Test Set Generation 🧪
Generated a test set of 60 questions using the generate_testset function from the giskard.rag library. This test set is the backbone of evaluating the chatbot's accuracy. 📊

5. Evaluation Metrics 📏
Developed a framework to evaluate the chatbot's responses against the test set. 🧐

Analyzed the performance of different RAG components: generator, retriever, rewriter, and routing mechanisms. 🔍

6. Results Visualization 📊
Created a comprehensive report to visualize the chatbot's performance metrics. 📈

Highlighted areas for improvement, especially in the rewriter component, to better handle conversational queries. 💬

🚀 Getting Started
Ready to dive in? Here’s how you can replicate this project:

1. Clone the Repository 📂
bash
Copy
git clone <repository-url>
cd RAG-Evaluation
2. Set Up Environment 🌱
Create a virtual environment and activate it.

Install the required packages:

bash
Copy
pip install -r requirements.txt
3. Configure Environment Variables 🔐
Create a .env file in the root directory and add your OpenAI API key:

plaintext
Copy
OPENAI_API_KEY=your_api_key_here
4. Run the Notebook 📓
Open the Jupyter notebook:

bash
Copy
jupyter notebook RAG-Evaluation/notebook.ipynb
🎯 Conclusion
This project has been a game-changer in understanding how to build and evaluate RAG applications. By combining web scraping, document processing, and machine learning, we’ve created a chatbot that can handle complex queries with ease. 🧠💡

Future work will focus on refining the chatbot's capabilities and expanding the knowledge base for even better performance. 🚀







