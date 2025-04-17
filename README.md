# Smart Research Assistant

A Jupyter Notebook-based tool that uses Google's Gemini AI to analyze PDF documents, generate summaries, and answer questions about their content. Perfect for researchers and students who need quick insights from research papers and documents.

![Smart Research Assistant](https://img.shields.io/badge/Status-Active-brightgreen)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-orange)

## Overview

The Smart Research Assistant helps you quickly understand PDF documents by providing intelligent summaries and answering questions about their content. It uses Google's Gemini AI to process documents and generate insights, making research more efficient and accessible.

## Features

### 📄 PDF Document Processing
- Upload and process PDF files
- Extract text content efficiently
- Handle various PDF formats
- Automatic text extraction and formatting

### 📝 Intelligent Summarization
- Generate structured summaries with:
  - Main topic/title
  - Key points
  - Overall summary
  - Related topics
- Clean, readable output format
- Context-aware analysis

### ❓ Interactive Question Answering
- Ask questions about document content
- Get context-aware answers
- View source context for answers
- Intelligent response generation

## Technical Implementation

### Core Components
- **Google Gemini AI**: Powers document analysis and question answering
- **PyPDF2**: Handles PDF text extraction
- **ipywidgets**: Creates interactive Jupyter Notebook interface
- **Python-dotenv**: Manages API key configuration

### Key Gen AI Capabilities
1. **Structured Output/JSON Mode**
   - Intelligent JSON formatting
   - Controlled generation
   - Robust error handling
   - Fallback mechanisms

2. **Document Understanding**
   - Comprehensive text extraction
   - Semantic understanding
   - Context-aware processing
   - Intelligent analysis

3. **Long Context Window**
   - Efficient document handling
   - Smart text truncation
   - Context preservation
   - Memory-efficient processing

4. **Grounding**
   - Source context with answers
   - Document-based responses
   - Content preservation
   - Reference tracking

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Tempest00/Smart-Research-Assistant.git
cd smart-research-assistant
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Set up your Google API key:
   - Create a `.env` file in the project root
   - Add your API key: `GOOGLE_API_KEY=your_api_key_here`

## Usage

1. **Upload a PDF**
   - Click the "Upload PDF" button
   - Select your document
   - Wait for processing confirmation

2. **Generate Summary**
   - Click "Get Summary" after successful upload
   - View the structured summary with key points

3. **Ask Questions**
   - Type your question in the input field
   - Click "Ask Question"
   - View the answer with source context

## Best Practices

### Document Size
- Keep PDFs under 4000 characters for optimal processing
- Larger documents will be automatically truncated

### Question Formatting
- Be specific in your questions
- Use clear, concise language
- Focus on key concepts

## Future Enhancements

- Multi-document support
- Advanced analysis features
- Export capabilities
- Enhanced UI/UX
- Additional document formats

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Google Gemini AI team
- PyPDF2 developers
- Jupyter and ipywidgets communities

## Contact

sharma41abhay@gmail.com