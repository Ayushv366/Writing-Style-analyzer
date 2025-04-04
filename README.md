# Writing-Style-analyzer
Web app that checks grammar, readability (Flesch/Fog Index), and writing style using Python/Flask. Features:  Grammar &amp; spell check  Readability scoring  Style improvements  One-click fixes  Easy setup: pip install flask &amp;&amp; python app.py  Open-source ✨ Perfect for students &amp; writers!

## Overview

The Writing Style Analyzer is a comprehensive web application designed to help writers improve their work through advanced text analysis. Built with Python's Flask framework, this tool provides:

- **Grammar and Spelling Correction** (powered by LanguageTool API)
- **Readability Scoring** (Flesch Reading Ease, Gunning Fog Index, Automated Readability Index)
- **Style Analysis** (passive voice detection, sentence length variation, word repetition)
- **Text Improvement** (one-click rewriting suggestions)

## Key Features

### 1. Grammar Checking
- Identifies spelling mistakes, punctuation errors, and grammatical issues
- Provides suggested corrections with explanations
- Supports multiple English variants (US/UK)

### 2. Readability Analysis
- Calculates 8 different readability metrics
- Estimates required education level to understand text
- Highlights complex sentences and difficult words

### 3. Style Enhancement
- Detects overuse of passive voice
- Flags word and phrase repetition
- Analyzes sentence length variation
- Suggests more concise alternatives

### 4. Text Improvement
- Automatic rewriting of problematic sections
- Preserves original meaning while improving clarity
- Copy-to-clipboard functionality for easy use

## Technical Implementation

### Backend (Python/Flask)
- **textstat** library for readability metrics
- **LanguageTool API** for grammar checking
- Custom algorithms for style analysis
- Text processing and improvement logic

### Frontend
- Clean, responsive interface
- Tabbed results display
- Real-time word counting
- Interactive improvement tools

## Installation

1. Clone the repository
git clone https://github.com/Ayushv366/writing-style-analyzer.git
cd writing-style-analyzer

2.Install dependencies:
pip install -r requirements.txt

3.Run the application:
python app.py

***4.Access the app at:***
http://localhost:5000

***Note***
use cmd to run the commands.

***Usage***
1.Paste your text into the input box
2.Click "Analyze Text" for comprehensive feedback
3.Review results in the tabs:
Readability scores
Grammar issues
Style suggestions
Click "Improve Text" for automatic corrections
Copy the improved text to clipboard

***Project Structure***
writing-style-analyzer/
├── app.py                # Flask application
├── requirements.txt      # Python dependencies
├── static/
│   ├── style.css         # Stylesheet
│   └── script.js         # Client-side functionality
├── templates/
│   └── index.html        # Main interface

## Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request
4. Report issues in the GitHub issue tracker

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Future Enhancements

- User accounts for saving analyses
- Additional language support
- Document upload functionality
- Browser extension version
- API access for developers

*******************Thanks***********************
