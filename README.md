# RAG_Step
# 📚 RAG-Based Document Question Answering System

A Retrieval-Augmented Generation (RAG) application that allows users to ask questions about documents and receive context-aware answers using Google's Gemini API.

## 🚀 Run in Google Colab

Click the button below to open the notebook in Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Arjun-glitch66/RAG_Step/blob/main/RAG_v2.ipynb)

## 📂 Project Structure

```text
RAG_Step/
├── RAG_v2.ipynb
├── README.md
└── data/
    ├── leave_policy_plan.pdf
    ├── posh_applicability_checker_expa...
    ├── project_management_activities_...
    └── remote_work_policy.txt
```

The `data/` directory contains the four documents used as the knowledge base for the RAG pipeline.

## ⚙️ Setup Instructions

### Step 1: Open the Notebook

1. Click the **Open in Colab** button above.
2. Connect to a Google Colab runtime.
3. Run the notebook cells in order.

### Step 2: Upload the Documents

The notebook requires four documents stored in the `data/` directory.

1. Open the [`data` folder](./data) in this repository.
2. Download all four documents to your computer.
3. Return to the Colab notebook.
4. Run the document upload cell.
5. Select all four downloaded files when the upload dialog appears.

The notebook will place the uploaded documents in the required project directory.

### Step 3: Configure Your Gemini API Key

Each user must configure their own Gemini API key.

1. Visit [Google AI Studio](https://aistudio.google.com/apikey).
2. Create an API key.
3. Open the **Secrets** panel in the left sidebar of Google Colab (key icon).
4. Add a new secret with the name:

   `GEMINI_API_KEY`

5. Paste your API key as its value.
6. Enable notebook access for this secret.

**Security:** Never paste your API key into the notebook or commit it to GitHub. Use Colab Secrets to keep it private.

### Step 4: Run the Application

After uploading the documents and configuring your API key, execute the notebook cells from top to bottom. You can then use the RAG pipeline to retrieve relevant document context and generate answers.

## 🛠️ Technologies Used

- Python
- Google Colab
- Gemini API
- Retrieval-Augmented Generation (RAG)
- Document processing and retrieval

## 📝 Notes

- A Google account is required to use Google Colab.
- Each user must provide their own Gemini API key.
- API usage is subject to applicable quotas, rate limits, and billing policies.
- The notebook's document upload step must be completed in each new runtime when the files are not already available.

## 👨‍💻 Author

**Arjun-glitch66**

GitHub: [@Arjun-glitch66](https://github.com/Arjun-glitch66)
