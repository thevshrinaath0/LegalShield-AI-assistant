# LegisLens - Hackathon Project

## 🚀 Project Overview
**LegisLens** is a GenAI-powered tool designed to help Small and Medium Enterprises (SMEs) in India navigate complex legal contracts. It democratizes access to legal expertise by providing instant, easy-to-understand risk analysis and high-quality contract drafting.

### 💡 Problem Statement
SMEs often struggle with:
*   **High Legal Costs:** Hiring lawyers for every contract review is expensive.
*   **Complex Jargon:** Legal language is difficult for non-lawyers to understand.
*   **Hidden Risks:** Unfair clauses (like unilateral termination or unlimited indemnity) often go unnoticed.

### ✅ Solution
Our solution provides:
1.  **AI Risk Analysis:** Instantly scans PDF/DOCX contracts and flags "High Risk" clauses (Red/Orange/Green indicators).
2.  **Multilingual Support:** Understands contracts in English and Indian languages (via translation).
3.  **Automated Drafting:** Generates balanced, "Low Risk" templates for Employment, Rental, and Vendor agreements.
4.  **Negotiation Assistant:** drafts professional emails to negotiate unfair clauses.

---

## 🛠️ Tech Stack
*   **Frontend:** Streamlit (Python)
*   **AI Engine:** Anthropic Claude 3 Haiku (via API)
*   **NLP:** spaCy (Entity Extraction)
*   **Processing:** PyPDF2, python-docx

---

## 📂 Project Structure
*   `app.py`: Main Streamlit application entry point.
*   `utils/nlp_engine.py`: Core logic for interacting with Claude 3 and spaCy.
*   `views/`: UI components for Dashboard, Templates, and Analysis.

---

## 🏃‍♂️ How to Run Locally
1.  Clone the repository.
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3.  Set up your `.env` file with `ANTHROPIC_API_KEY`.
4.  Run the app:
    ```bash
    streamlit run app.py
    ```

## 🎥 Demo
[Insert your YouTube/Google Drive Link Here]
