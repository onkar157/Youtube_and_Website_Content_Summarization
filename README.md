# ▶️ Youtube and Website Content Summarization



A Generative AI application that extracts and summarizes content from YouTube videos and websites. This app uses advanced tools and models to provide concise and accurate summaries, making it easier to grasp the essence of the content.

<br>

## 🚀 Features

- **YouTube Video Summarization**: Extracts and summarizes transcripts from YouTube videos.
- **Website Summarization**: Summarizes content from web pages using their URLs.
- **Advanced Models**:
  - **YouTubeLoader**: Efficiently processes video URLs to fetch transcripts.
  - **UnstructuredURLLoader**: Handles and parses content from websites.
  - **Load Summarize Chain**: Powers the summarization process.
  - **Gemma Model (Groq API)**: Generates high-quality summaries with advanced language understanding.
- **User-Friendly Input**: Accepts video or website URLs for seamless operation.
<br>


## 🛠️ Tech Stack

- **Python**: Core programming language for the application.
- **LangChain**: Framework for handling the summarization chain.
- **Groq API**: Utilized for deploying the Gemma Model.
- **Streamlit**: For building an interactive user interface.

<br>

## 📦 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-repo/gen-ai-summarizer.git
cd gen-ai-summarizer
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Set Up API Keys
- Obtain your Groq API key and add it to an `.env` file:
  ```env
  GROQ_API_KEY=your-api-key
  ```

### 4. Run the Application
```bash
streamlit run app.py
```

<br>

## 🧩 How It Works

1. **Input URL**:
   - Enter the YouTube video URL or the website URL in the app interface.

2. **Content Processing**:
   - For YouTube videos: The app fetches and processes the video transcript using **YouTubeLoader**.
   - For websites: The app parses the content using **UnstructuredURLLoader**.

3. **Summarization**:
   - The **Load Summarize Chain** integrates the content with the **Gemma Model** via the Groq API to generate a concise and meaningful summary.

4. **Output**:
   - The app displays the summarized content in a user-friendly format.

<br>

## ⚡ Benefits

- Simplifies content consumption by providing concise summaries.
- Saves time by extracting key points from lengthy videos or articles.
- Supports diverse content types, enhancing flexibility.

<br>

## 🚧 Future Enhancements

- Add support for multilingual summarization.
- Enable downloading summaries in text or PDF format.
- Provide advanced customization for summary length and tone.

<br>

## 🤝 Contribution

Contributions are welcome! Feel free to fork the repository and submit pull requests with your improvements or suggestions.
<br>
<br>
## 🌟 Acknowledgments

- **LangChain** for its robust summarization framework.
- **Groq API** for enabling the use of the Gemma Model.
- **YouTubeLoader and UnstructuredURLLoader** for their efficient content processing capabilities.
