# 💼 ClarityX: Transforming Business with AI

ClarityX is an advanced RAG (Retrieval-Augmented Generation) based AI-powered business assistant. It enables users to extract actionable financial strategies and insights from industry-standard documents, empowering businesses with data-driven decision-making capabilities.

---

## 🚀 Features

- **Context-Aware Strategy Generation**: Input a financial question and get a detailed, actionable strategy derived from your document repository.
- **Advanced LLM Integration**: Powered by `Mistral-7B-Instruct-v0.3` via Hugging Face Inference API.
- **Robust Vector Store**: Qdrant-based in-memory vector storage for efficient document retrieval.
- **PDF Parsing**: Extract text seamlessly from PDFs using `pdfplumber`.
- **Streamlit Interface**: User-friendly web app interface with an intuitive workflow.
- **CSV Insights (Future Scope)**: Upload CSV files to visualize data insights and generate additional analytics.

---

## 🛠️ Technology Stack

- **Frontend**: [Streamlit](https://streamlit.io/) for a responsive and interactive user interface.
- **LLM**: [Mistral-7B-Instruct-v0.3](https://huggingface.co/mistralai) via Hugging Face Inference API.
- **Vector Store**: [Qdrant](https://qdrant.tech/) for efficient similarity search and retrieval.
- **PDF Parsing**: [pdfplumber](https://github.com/jsvine/pdfplumber) for text extraction from PDF documents.
- **Environment Variables**: `.env` file management via `python-dotenv`.

---

## 🖥️ Setup and Installation

### Prerequisites

- Python 3.9+
- Streamlit 1.25+
- Hugging Face API token

### Installation Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/clarityx.git
   cd clarityx
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up Environment Variables**:
   - Create a `.env` file in the project root.
   - Add your Hugging Face API token:
     ```
     HF_TOKEN=your_huggingface_api_token
     ```

4. **Run the Application**:
   ```bash
   streamlit run app.py
   ```

---

## 🧩 How It Works

1. **Document Loading**: Load and parse documents (e.g., PDFs) into vectorized representations using Qdrant.
2. **Query Processing**: Input your business question through the Streamlit interface.
3. **Context Retrieval**: Relevant document excerpts are retrieved based on the input query.
4. **LLM-Driven Strategy**: Generate detailed financial strategies using context-aware prompts.
5. **Results Display**: Strategies are presented in an organized, tabbed layout for clarity.

---

## 🎨 User Interface

### Main Interface
- **Header**: Displays the app title and tagline.
- **Input Field**: Allows users to enter a financial question.
- **Submit Button**: Triggers the retrieval and strategy generation process.
- **Tabs**: Organizes the generated strategies and (optional) data insights.

### Sidebar
- Step-by-step instructions on using the assistant.

---

## 📂 Folder Structure

```
clarityx/
├── app.py                  # Main application script
├── requirements.txt        # Python dependencies
├── data/                   # Directory for storing PDFs
├── .env                    # Environment variables
├── README.md               # Project documentation
└── ...
```

---

## 🤝 Contributing

We welcome contributions to ClarityX! To contribute:
1. Fork this repository.
2. Create a new branch (`feature/new-feature`).
3. Commit your changes.
4. Push to your branch and submit a Pull Request.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🧠 Future Enhancements

- Add support for real-time CSV data analysis and visualization.
- Enhance document parsing for non-PDF formats.
- Expand LLM capabilities for multi-lingual financial strategies.
- Deploy the app on a cloud platform for wider accessibility.

---

## 🙌 Acknowledgments

- [Streamlit](https://streamlit.io/) for the intuitive app framework.
- [Hugging Face](https://huggingface.co/) for powerful LLMs.
- [Qdrant](https://qdrant.tech/) for efficient vector search.
- [pdfplumber](https://github.com/jsvine/pdfplumber) for seamless PDF text extraction.

---

## 📧 Contact

For queries or feedback, feel free to reach out at [your-email@example.com](mailto:your-email@example.com).

---

> © 2024 ClarityX - Financial Strategy Assistant
