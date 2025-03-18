AI Resume Screening & Candidate Ranking System

📌 Introduction
In modern recruitment, companies receive a large number of resumes for every job opening. Manually screening these resumes is time-consuming. This project uses **AI and NLP** to automate resume screening and rank candidates based on job descriptions.

🚀 Features
- Extracts text from resumes (PDFs)
- Compares resumes with job descriptions
- Uses **TF-IDF & Cosine Similarity** for ranking
- Displays the top-ranked resumes
- Web app built with **Streamlit**

🛠️ Tech Stack
- **Frontend:** Streamlit
- **Backend:** Python
- **Libraries:** Scikit-learn, NLTK, SpaCy, PyPDF2
- **Deployment:** Streamlit Cloud

📂 Dataset
The dataset consists of resumes in PDF format. **TF-IDF vectorization** is applied for text processing.

🏗️ How to Run the Project
1. Clone the repository:
   ```sh
   git clone <repo_link>
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```

🔮 Future Scope
- Integrate **BERT/GPT** for better semantic matching
- Improve **resume parsing** for structured data extraction
- Add **multi-language support** for a wider audience
- Enhance security and scalability

📜 License
This project is for educational purposes only.

---
💡 **Contributors:** [Potpally Joseph Raj]
