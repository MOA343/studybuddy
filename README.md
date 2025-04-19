# Study Buddy

Study Buddy is an AI-powered application that transforms educational videos and audio recordings into interactive flashcards. Perfect for students and lifelong learners, this tool helps you extract key concepts from lectures and study more efficiently.

![Study Buddy Screenshot](screenshot.png)

## 🚀 Features

- **Audio/Video Upload**: Support for various formats including MP3, WAV, OGG, MP4, and WEBM
- **AI Transcription**: Converts spoken content into written text
- **Automatic Flashcard Generation**: Identifies important concepts and creates study cards
- **Interactive UI**: Toggle between flashcards and full transcription
- **Responsive Design**: Works on desktop and mobile devices

## 🔧 Technologies Used

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express
- **AI Services**: 
  - Google Speech-to-Text API for transcription
  - OpenAI API for flashcard generation
- **File Handling**: Multer, fluent-ffmpeg

## 📋 Prerequisites

Before you begin, ensure you have:

- Node.js (v14.x or later)
- npm (v6.x or later)
- Google Cloud account with Speech-to-Text API enabled
- OpenAI API key

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/study-buddy.git
   cd study-buddy
   ```

2. **Install dependencies**
   ```bash
   npm run install-all
   ```

3. **Create environment files**
   
   Create a `.env` file in the server directory:
   ```
   PORT=5001
   OPENAI_API_KEY=your_openai_key_here
   ```

4. **Add Google Cloud credentials**
   
   Place your Google Cloud service account key in `server/config/google_credentials.json`

## 🚀 Running the Application

1. **Start both frontend and backend**
   ```bash
   npm start
   ```

2. **Access the application**
   
   Open your browser and navigate to `http://localhost:3000`

## 🧪 Using Mock Services

If you don't have API keys or want to test without using external services:

1. The application includes mock implementations for both transcription and flashcard generation
2. These are enabled by default in `server/services/aiService.js`
3. To use real services, uncomment the relevant sections and add your API keys

## 📝 How to Use

1. **Upload a file**: Click "Browse Files" or drag and drop a lecture audio/video file
2. **Process**: Click "Process File" and wait for the AI to work its magic
3. **Study**: Browse through the generated flashcards or review the full transcription
4. **Toggle views**: Switch between flashcard and transcription modes

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgements

- [Google Cloud Speech-to-Text](https://cloud.google.com/speech-to-text)
- [OpenAI](https://openai.com/)
- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Express](https://expressjs.com/)

---

Created with ❤️ by [Your Name]
