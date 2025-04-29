# NLP Text Analyzer

**Note:** This project is currently under active development. Features may be added, changed, or improved over time.

## Description

A web-based tool for performing various Natural Language Processing (NLP) analyses on user-provided text. This application allows users to paste text, upload text files, or use sample text to generate summaries, extract key phrases, perform sentiment analysis, and view text statistics. A key goal of this project was to make it as functional as possible using only client-side technologies (HTML, CSS, and JavaScript) without relying on a backend.

## Features

* **Text Input:**
    * Paste text directly into the text area.
    * Upload `.txt` files.
    * Load sample text for quick testing.
* **Analysis Options:**
    * **Text Summarization:** Generate a concise summary of the input text. The target length is adjustable via a slider (10% to 70%).
    * **Key Phrase Extraction:** Identify and list the most significant terms or phrases in the text.
    * **Sentiment Analysis:**
        * Determine the overall sentiment (Positive, Negative, Neutral) of the text.
        * Provide sentence-level sentiment breakdown with scores.
    * **Feature Selection:** Choose which analyses (Summarization, Key Phrases, Sentiment) to perform.
* **Results Display:**
    * Organized into tabs: Summary, Key Phrases, Sentiment, Statistics.
    * Visual sentiment meter for overall score.
    * Detailed text statistics: word count, sentence count, character count, estimated reading time, average sentence length, percentage of positive/neutral/negative sentences.
    * Copy buttons for easily grabbing the generated summary or key phrases.
* **User Experience:**
    * Responsive design for various screen sizes.
    * Loading indicator with progress simulation during analysis.
    * Keyboard shortcuts: `Ctrl/Cmd+Enter` to analyze, `Ctrl/Cmd+L` to load sample text.
    * Informative alerts and word count display.

## How to Use

1.  Open the `nlp_text_analyzer.html` file in your web browser.
2.  **Input Text:**
    * Paste your text into the main text area, OR
    * Click "Upload .txt File" to select a local file, OR
    * Click "Load Sample" to populate the text area with example content.
3.  **Configure Options:**
    * Adjust the "Summary Length" slider if summarization is enabled.
    * Check/uncheck the boxes under "Analysis Features" to select the desired analyses.
4.  **Analyze:** Click the "Analyze Text" button or press `Ctrl+Enter` (or `Cmd+Enter` on Mac).
5.  **View Results:** The analysis results will appear below in their respective tabs. Navigate through the tabs (Summary, Key Phrases, Sentiment, Statistics) to see the different outputs.
6.  **Copy Results:** Use the "Copy Summary" or "Copy Phrases" buttons within the corresponding tabs to copy the text to your clipboard.

## Technologies Used

* HTML5
* CSS3 (including CSS variables for theming)
* JavaScript (for DOM manipulation, client-side text processing logic, and UI interactions)

## Author

GitHub: [@husal90](https://github.com/husal90)
