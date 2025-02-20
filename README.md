# Generative AI-powered Chatbot for SOPs

This project is a **Generative AI-powered Chatbot** trained on internal **Standard Operating Procedures (SOPs)** to provide real-time insights into operational processes.

---

## 🛠️ Features

- **AI Model**: 
  - Powered by **Llama** from Hugging Face, fine-tuned using a dataset of internal SOP documents.

- **RAG Pipeline**: 
  - Implements a **Retrieval-Augmented Generation (RAG)** pipeline using **FAISS** for accurate and contextually relevant responses.

- **Data Extraction & Processing**:
  - **Extraction**: Handled using the **Docling** library.
  - **Chunking Strategy**: Utilizes **semantic chunking** to ensure meaningful text segments.
  - **Query Expansion Strategy**: Applied to enhance retrieval accuracy.
  - **Confidential Data**: The exact **DOCX documents** used for training cannot be shared as they contain confidential information. These documents exist in **various structures**, which were preprocessed accordingly.

- **User Interface**: 
  - Built with **Streamlit** for an intuitive and interactive experience.

- **Local Hosting**: 
  - Hosted locally with **Ollama**, ensuring data privacy and fast response times.

---

## 🧑‍💻 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/ai-chatbot-sop.git
   cd ai-chatbot-sop
   ```

2. **Create a Virtual Environment & Install Dependencies**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```

3. **Run the Chatbot**
   ```bash
   streamlit run chatbot.py
   ```

---

## 📚 Resources

Here are some resources for understanding the core technologies used in this project:

- [Hugging Face Llama](https://huggingface.co/docs): Comprehensive guide on Hugging Face models and tools. 🧑‍💻📚
- [FAISS](https://faiss.ai/): Guide to the FAISS library for efficient similarity search and retrieval. 📖🔧
- [Streamlit Documentation](https://docs.streamlit.io/): Explore how to build interactive applications with Streamlit. 🌟📚
- [Ollama](https://ollama.com/): Learn about hosting models locally with Ollama for privacy and speed. 🚀📖

---

## 📝 Contributing

Contributions are welcome! If you have suggestions or improvements, please **fork the repository** and submit a **pull request**. For major changes, please open an **issue** to discuss your ideas.

---

## 📧 Contact

For any questions or feedback, feel free to reach out to me at satwikpothineni@gmail.com.

---

## 🔗 Credits

Special thanks to:

- Hugging Face for their Llama model.
- Ollama for local model hosting.
- FAISS for the efficient retrieval mechanism.
- Streamlit for providing an easy-to-use framework for building interactive web apps.

---

Happy coding! 🚀🎉
