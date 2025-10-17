# 📄 AI-Powered Resume Builder

An intelligent resume builder application that uses OpenAI's GPT-4 to optimize your resume for specific job positions. Built with Python and Streamlit for easy deployment.

## ✨ Features

- **AI-Powered Optimization**: Uses OpenAI GPT-4 to tailor your resume to specific job descriptions
- **Multiple Input Formats**: Upload resumes in TXT, PDF, or DOCX format, or paste directly
- **Professional Formatting**: Generates ATS-friendly resumes with proper structure
- **Multiple Download Options**: Download your optimized resume as TXT or DOCX
- **Modern UI**: Clean, intuitive interface built with Streamlit
- **Keyword Optimization**: Automatically incorporates relevant keywords from job descriptions

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- OpenAI API key

### Installation

1. **Clone or navigate to the project directory**

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up your environment variables**
   
   Make sure your `.env` file contains your OpenAI API key:
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```

### Running Locally

Run the Streamlit application:

```bash
streamlit run app.py
```

The application will open in your default web browser at `http://localhost:8501`

## 📱 Usage

1. **Enter Your Name**: Provide your full name for the resume
2. **Upload Your Resume**: Either upload a file (TXT, PDF, DOCX) or paste your resume text
3. **Add Job Description**: Paste the target job description or position requirements
4. **Generate**: Click the "Generate Optimized Resume" button
5. **Download**: Download your optimized resume in TXT or DOCX format

## 🌐 Deploying to Streamlit Cloud

1. **Push your code to GitHub** (make sure `.env` is in `.gitignore`)

2. **Go to [Streamlit Cloud](https://streamlit.io/cloud)**

3. **Deploy your app**:
   - Click "New app"
   - Select your repository
   - Set the main file path to `app.py`
   - Add your secrets in the "Advanced settings" → "Secrets" section:
     ```toml
     OPENAI_API_KEY = "your_openai_api_key_here"
     ```

4. **Click Deploy**

## 🔒 Security Notes

- **Never commit your `.env` file** to version control
- When deploying to Streamlit Cloud, use the Secrets management feature
- Keep your API keys secure and rotate them regularly

## 🛠️ Technologies Used

- **Streamlit**: Web application framework
- **OpenAI GPT-4**: AI-powered resume generation
- **python-docx**: Word document creation
- **PyPDF2**: PDF file processing
- **python-dotenv**: Environment variable management

## 📝 Tips for Best Results

- Provide a complete original resume with all your experience and skills
- Include a detailed job description with specific requirements
- Review and customize the generated resume before using it
- The AI maintains truthfulness - it only uses information from your original resume

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📄 License

This project is open source and available for personal and commercial use.
