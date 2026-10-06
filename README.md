# 📊 Text Statistics Analyzer

A simple and interactive web-based **Text Statistics Analyzer** that examines written text and provides useful statistical information such as word count, character count, sentence count, paragraph count, reading time, average word length, and frequently used words.

This project demonstrates basic **Natural Language Processing (NLP)** and text-processing concepts using HTML, CSS, and JavaScript.

---

## 📌 Project Overview

The **Text Statistics Analyzer** allows users to enter or paste text and instantly analyze its structure.

The application processes the text using JavaScript and generates detailed statistics through an interactive dashboard.

It works completely in the browser and does not require an external API, backend server, or database.

---

## 🎯 Objectives

* Analyze the structure of written text.
* Count words, characters, sentences, and paragraphs.
* Detect numbers and letters.
* Calculate estimated reading time.
* Calculate average word length.
* Calculate average sentence length.
* Identify frequently used words.
* Present results using visual statistics.
* Store recent analyses using LocalStorage.

---

## ✨ Features

* 🔤 Character counter
* 📝 Word counter
* 📄 Sentence counter
* 📌 Paragraph counter
* 🔢 Number counter
* ⏱️ Reading-time estimation
* 📏 Average word length
* 📖 Average sentence length
* 🔠 Letter count
* ␠ Space count
* 🔝 Frequently used word detection
* 📊 Visual progress bars
* 🕘 Recent analysis history
* 💾 LocalStorage support
* 📱 Responsive interface
* 🧹 Clear/reset option

---

## 🛠️ Technologies Used

* **HTML5** — Page structure
* **CSS3** — Styling and responsive layout
* **JavaScript** — Text processing and calculations
* **LocalStorage** — Recent analysis storage
* **Regular Expressions** — Text pattern detection

---

## 🧠 How It Works

The application follows this process:

```text
User enters text
       ↓
Text preprocessing
       ↓
Extract words
       ↓
Count characters
       ↓
Count words
       ↓
Count sentences
       ↓
Count paragraphs
       ↓
Detect numbers and letters
       ↓
Calculate reading time
       ↓
Calculate average lengths
       ↓
Find frequent words
       ↓
Display statistics
       ↓
Save analysis history
```

---

## 📊 Statistics Provided

### 1. Character Count

Counts the total number of characters present in the entered text.

Example:

```text
Hello World
```

Character count:

```text
11
```

---

### 2. Word Count

Counts individual words using text pattern matching.

Example:

```text
Artificial intelligence is useful.
```

Word count:

```text
5
```

---

### 3. Sentence Count

Detects sentences based on punctuation such as:

```text
.
!
?
```

Example:

```text
Hello. How are you?
```

Sentence count:

```text
2
```

---

### 4. Paragraph Count

Detects separate paragraphs based on blank lines.

---

### 5. Number Count

The application detects numerical values such as:

```text
10
2026
3.14
500
```

---

### 6. Reading Time

The application estimates reading time using an average reading speed of approximately:

```text
200 words per minute
```

For example:

```text
400 words ≈ 2 minutes
```

---

### 7. Average Word Length

The application calculates the average number of letters contained in each word.

Formula:

```text
Average Word Length =
Total Letters in Words / Total Words
```

---

### 8. Average Sentence Length

Formula:

```text
Average Sentence Length =
Total Words / Total Sentences
```

The result is displayed in words per sentence.

---

## 🔝 Frequent Word Analysis

The application identifies the most frequently used meaningful words.

Common stop words such as:

```text
the
is
a
an
and
or
of
to
in
on
for
```

are ignored to make the results more useful.

Example:

```text
AI AI technology technology technology
```

Result:

```text
technology ×3
AI ×2
```

---

## 💾 LocalStorage

The application stores the latest five text analyses in the browser.

Storage key:

```text
textStatsHistory
```

The stored information includes:

* Entered text
* Word count
* Sentence count
* Analysis time

No external database is required.

---

## 📁 Project Structure

```text
TextStatisticsAnalyzer/
│
├── index.html
└── README.md
```

The complete application is contained in a single HTML file.

The file includes:

* HTML
* CSS
* JavaScript

---

## 🚀 How to Run in VS Code

### Step 1 — Create the Project Folder

Create:

```text
TextStatisticsAnalyzer
```

### Step 2 — Open in VS Code

Open the folder using Visual Studio Code.

### Step 3 — Create the HTML File

Create:

```text
index.html
```

### Step 4 — Add the Code

Paste the complete Text Statistics Analyzer code into `index.html`.

### Step 5 — Run the Project

You can:

* Open `index.html` directly in a browser, or
* Use the **Live Server** extension in VS Code.

### Step 6 — Test

Enter or paste some text and click:

```text
Analyze Text
```

---

## 🧪 Sample Input

```text
Artificial intelligence is changing the world. Students are using AI tools to learn programming, analyze data, and build innovative applications. Technology makes learning faster and more accessible.
```

The application will generate statistics including:

```text
Characters
Words
Sentences
Paragraphs
Numbers
Reading Time
Average Word Length
Average Sentence Length
Letters
Spaces
Frequently Used Words
```

---

## 📋 Sample Test Cases

| Input                             | Expected Result      |
| --------------------------------- | -------------------- |
| Hello world.                      | 2 words, 1 sentence  |
| I love programming!               | 3 words, 1 sentence  |
| Python is easy. Java is powerful. | 6 words, 2 sentences |
| AI 2026 is amazing.               | Number detected      |
| Hello. How are you?               | 2 sentences          |

---

## 🔐 Privacy

The application performs text analysis locally in the browser.

The entered text is not sent to an external server or third-party API.

Recent analyses are stored locally using the browser's LocalStorage.

---

## ⚠️ Limitations

This project is designed for educational purposes and uses basic text-processing techniques.

It may have limitations when processing:

* Abbreviations
* Complex punctuation
* Multiple-line documents
* Special characters
* Non-English languages
* Very complex sentence structures
* Context-dependent meanings

Sentence detection is based primarily on punctuation rather than advanced linguistic analysis.

---

## 🔮 Future Enhancements

The project can be extended with:

* 📊 Interactive charts
* ☁️ Cloud storage
* 👤 User authentication
* 🌍 Multilingual text analysis
* 🧠 Advanced NLP
* 🔎 Keyword extraction
* 📚 Readability score
* 📈 Text comparison
* 📄 PDF/DOCX file upload
* 🤖 AI-powered text analysis
* 🔊 Speech-to-text integration
* 📱 Progressive Web App support

---

## 🎓 Academic Applications

This project can be used for:

* NLP mini projects
* Web technology projects
* CSE laboratory demonstrations
* Text processing experiments
* Artificial Intelligence projects
* Data analysis demonstrations
* Mini project presentations

---

## 📚 Concepts Demonstrated

* Text preprocessing
* String manipulation
* Regular expressions
* Word counting
* Sentence detection
* Character analysis
* Frequency analysis
* JavaScript DOM manipulation
* Event handling
* LocalStorage
* Responsive web design
* Basic NLP concepts

---

## 👩‍💻 Author

**Charulatha S**

B.E. Computer Science Engineering
Prathyusha Engineering College

---

## 📌 Project Series

This project is:

**Application 3 of 10 — Text & Speech Analysis Applications**

### Series

1. ✅ Text Sentiment Analyzer
2. ✅ Text Emotion Detector
3. ✅ **Text Statistics Analyzer**
4. ⏳ Keyword & Topic Extractor
5. ⏳ Text Summarizer
6. ⏳ Speech-to-Text Analyzer
7. ⏳ Speech Emotion Analyzer
8. ⏳ Voice Command Application
9. ⏳ Speech Characteristics Analyzer
10. ⏳ Text & Speech Chat Assistant

---

## ⭐ Conclusion

The **Text Statistics Analyzer** provides a simple way to understand the structure and characteristics of written text.

It demonstrates how JavaScript and basic NLP techniques can be used to perform useful text analysis directly in a web browser. The project can later be extended with advanced NLP, AI models, cloud storage, and speech-processing capabilities.
