# Career Conversation with Sergei LERNER

An AI-powered career conversation chatbot that represents Sergei LERNER, built with Gradio and OpenAI's GPT-4.

## Features

- 🤖 AI-powered chatbot that acts as Sergei LERNER
- 💼 Career-focused conversations and Q&A
- 📧 User engagement tracking and email collection
- 📱 Push notifications for user interactions
- 🎯 Professional representation for potential clients and employers

## Technology Stack

- **Backend**: Python
- **AI**: OpenAI GPT-4
- **Web Interface**: Gradio
- **PDF Processing**: PyPDF
- **Notifications**: Pushover API

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Aputze/career_conversation.git
cd career_conversation
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up environment variables:
Create a `.env` file with the following variables:
```env
OPENAI_API_KEY=your_openai_api_key_here
PUSHOVER_TOKEN=your_pushover_token_here
PUSHOVER_USER=your_pushover_user_here
```

## Usage

Run the application:
```bash
python app.py
```

The chatbot will be available at the local URL provided by Gradio (typically `http://localhost:7860`).

## Project Structure

```
career_conversation/
├── app.py              # Main application file
├── requirements.txt    # Python dependencies
├── README.md          # Project documentation
├── me/                # Personal information
│   ├── linkedin.pdf   # LinkedIn profile
│   └── summary.txt    # Career summary
└── .gitignore         # Git ignore file
```

## Features

- **Career Representation**: The AI acts as Sergei LERNER, answering questions about career, background, skills, and experience
- **User Engagement**: Tracks user interactions and collects contact information
- **Question Recording**: Records questions that couldn't be answered for future improvement
- **Professional Interface**: Clean, professional web interface built with Gradio

## Contributing

This is a personal project for Sergei LERNER's career representation. For questions or suggestions, please reach out through the appropriate channels.

## License

This project is for personal use and career representation purposes.
