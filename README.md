# ⚡️ SummarizePro: YouTube Video Summarizer 📖

**SummarizePro** is a Streamlit-based application that generates **detailed summaries** of YouTube videos with a single click! Powered by the **Gemma2-9b-it** model from Google via Groq API and LangChain, it provides organized, concise, and accurate notes, making it perfect for quick insights or revisiting lengthy video content.

---

## 🚀 Features:
- **Instant Summaries**: Generates structured, detailed summaries of any YouTube video.  
- **User-Friendly**: Simply input a YouTube URL, and let AI do the rest!  
- **Powerful AI**: Uses Gemma2-9b-it for high-quality, precise summarization.  
- **Thumbnail Display**: Fetches and displays the video thumbnail for a better visual experience.  
- **Custom Prompt Template**: Summaries include:
  - **Introduction**
  - **Key Concepts**
  - **Important Details**
  - **Steps/Processes**
  - **Conclusion**
  - **Visuals/Examples**  

---

## 🛠️ Tech Stack:
- **Streamlit**: For an interactive, responsive user interface.  
- **LangChain**: To facilitate prompt engineering and LLM chains.  
- **Groq API**: Integration with the Gemma2-9b-it model.  
- **YouTubeLoader**: To extract content from YouTube videos.  
- **Python**: Core logic, prompt handling, and utility.  

---

## 🔧 Setup Instructions:

### Prerequisites:
- Python 3.8+
- Groq API Key (Get yours at [Groq API](https://groq.com/))

### Steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/summarizepro.git
   cd summarizepro
   ```

2. **Install Dependencies**:
   ```bash
   pip install streamlit langchain langchain-groq langchain-community validators nltk
   ```

3. **Download NLTK Data** (required for text processing):
   ```bash
   python -c "import nltk; nltk.download('punkt')"
   ```

4. **Run the Application**:
   ```bash
   streamlit run app.py
   ```

5. **Input Your Groq API Key** in the sidebar and provide a valid YouTube URL.

---

## 🎥 How to Use:
1. Open the app by running the command above.
2. Enter your **Groq API Key** in the sidebar.
3. Paste a valid **YouTube URL** into the text input box.
4. Click **Summarize**.
5. Wait while the app processes the video content and generates a summary.
6. View the summary along with the video thumbnail for quick reference.

---


## 🤝 Contributing:
Contributions are welcome! If you find any issues or have ideas for new features, feel free to open an issue or submit a pull request.

### Steps to Contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a Pull Request.

---
---

## 🌟 Acknowledgments:
- **Streamlit** for the web framework.
- **LangChain** for powerful LLM integration.
- **Groq** for providing the Gemma2-9b-it model.
- **YouTubeLoader** for extracting content from YouTube videos.

---


---

Enjoy SummarizePro ⚡️ and make video learning easier than ever!
