🤖 Advanced AI Text Summarizer

An Advanced AI Text Summarizer is a browser-based NLP project that automatically generates a concise summary from long text. The application uses extractive text summarization techniques, word-frequency analysis, sentence scoring, keyword extraction, and statistical analysis.

The complete project can run directly in a web browser using a single `index.html` file.

🚀 Features

✨ Extractive text summarization
🧠 NLP-based sentence scoring
📊 Text statistics and analysis
🔑 Important keyword extraction
📈 Summary compression percentage
📝 Custom summary length: 20%, 30%, 40%, or 50%
📋 Copy generated summary
⬇️ Download summary as a `.txt` file
📄 Built-in example text
🗑️ Clear input and results
⌨️ `Ctrl + Enter` keyboard shortcut
📱 Responsive user interface
🌙 Modern dark-themed dashboard

🧠 How It Works

The summarizer follows these main steps:

1. Input Text

   * The user enters an article, news report, research content, or any other text.

2. Text Tokenization

   * The application converts the text into individual words.
   * Special characters are removed and words are normalized.

3. Stop Word Removal

   * Common words such as `the`, `is`, `and`, `of`, and `to` are ignored during analysis.

4. Word Frequency Calculation

   * The frequency of meaningful words is calculated.

5. Sentence Scoring

   * Each sentence receives a score based on:

     * Word frequency
     * Sentence length
     * Position of the sentence
     * Keyword density
     * Presence of numbers

6. Sentence Selection

   * The highest-scoring sentences are selected according to the chosen summary percentage.

7. Summary Generation

   * Selected sentences are returned in their original order to create the final summary.

8. Keyword Extraction

   * The most frequently occurring meaningful words are displayed as important keywords.

📊 Text Analysis

The application displays:

| Metric        | Description                              |
| ------------- | ---------------------------------------- |
| Words         | Total number of words in the input       |
| Sentences     | Number of detected sentences             |
| Summary Words | Number of words in the generated summary |
| Compression   | Percentage of text reduced               |
| Keywords      | Frequently occurring meaningful words    |

The project calculates compression using the difference between the original word count and summary word count.

🛠️ Technologies Used

* HTML5 – Web page structure
* CSS3 – User interface and responsive design
* JavaScript – NLP processing and application logic
* NLP Techniques – Tokenization, stop-word removal, word frequency, sentence scoring
* Browser APIs – Clipboard and file download

No external libraries or backend server are required.

📁 Project Structure

text
Advanced-AI-Text-Summarizer/
│
├── index.html
└── README.md

💻 How to Run

Method 1: Using VS Code

1. Download or clone this repository.
2. Open the project folder in **Visual Studio Code**.
3. Open `index.html`.
4. Right-click the file.
5. Select **Open with Live Server**.

You can also simply open `index.html` directly in a web browser.

📌 Usage

1. Enter or paste a long text into the **Input Text** area.
2. Select the required summary length.
3. Click **Generate Summary**.
4. View the generated summary.
5. Check the text statistics and important keywords.
6. Click **Copy** to copy the summary.
7. Click **Download** to save the summary as a text file.

⚙️ Summary Length

The application provides four summary levels:

* 20% – Very short summary
* 30% – Short summary
* 40% – Medium summary
* 50% – Detailed summary

The selected percentage determines approximately how many sentences are selected from the original text.

🔑 Keyword Extraction

The system calculates word frequencies while ignoring predefined stop words. It then sorts the meaningful words by frequency and displays the top keywords with their occurrence counts.

Example:

text
artificial (5)
intelligence (4)
technology (3)
learning (3)
data (2)

📈 Sentence Scoring Algorithm

Each sentence is assigned a score using several factors:

text
Sentence Score =
Word Frequency Score
+ Length Normalization
+ Position Importance
+ Keyword Density
+ Number Detection

The first and second sentences receive additional importance because they may contain important introductory information. The final sentence also receives additional importance.

🎯 Applications

This project can be useful for:

* 📰 News article summarization
* 📚 Study material summarization
* 📄 Research paper summarization
* 📝 Notes generation
* 💼 Business document summarization
* 🌐 Web content summarization
* 🎓 Student academic projects
* 🔍 Basic NLP demonstrations

 🌟 Advantages

* Easy to use
* No installation required
* No API key required
* Works directly in the browser
* Fast processing
* Responsive design
* Provides both summary and text statistics
* Suitable for NLP learning and academic demonstrations

⚠️ Limitations

This project uses **extractive summarization**, meaning it selects important sentences from the original text rather than generating completely new sentences.

Therefore:

* The summary may contain sentences that are not perfectly connected.
* It does not understand text like a large language model.
* Summary quality depends on word frequency and sentence scoring.
* Very short texts may not produce a meaningful reduction.

🔮 Future Enhancements

The project can be improved by adding:

* Transformer-based summarization
* BERT summarization
* Text-to-speech output
* Speech-to-text input
* Multilingual summarization
* PDF and DOCX upload
* AI-generated abstractive summaries
* Sentiment analysis
* Named entity recognition
* Similarity-based sentence ranking
* Cloud-based AI API integration
* User history and saved summaries

📸 Project Interface

The interface contains:

* Input Text panel
* Generate Summary button
* Summary length selector
* Generated Summary panel
* Copy and Download buttons
* Text statistics dashboard
* Important Keywords section
* Summary Compression progress bar

The uploaded project implements these interface components in the single HTML application.

👨‍💻 Project Type

Project Category:Artificial Intelligence / Natural Language Processing

Project Title: Advanced AI Text Summarizer

Frontend: HTML, CSS, JavaScript

Processing: Client-side JavaScript NLP

Deployment: Web Browser

📜 License

This project is created for **educational and academic purposes**. You are free to modify and improve the project for learning and personal use.

⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.
🔥 Made with HTML, CSS, JavaScript & NLP
