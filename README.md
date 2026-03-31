# Secrexa — AI Personal Secretary

Secrexa is an AI-powered personal assistant designed to function as a digital secretary.
It listens to voice or text input, interprets tasks using advanced AI models, schedules them automatically, and delivers intelligent reminders — helping users manage their daily life with minimal effort.

---

## Features

- **Voice to Task Conversion** — Converts spoken input into structured, actionable tasks using speech recognition.
- **Smart Task Understanding** — Leverages AI to interpret natural language and extract intent, priority, and deadlines.
- **Automatic Task Scheduling** — Organizes and schedules tasks based on context and user preferences without manual intervention.
- **Intelligent Reminders** — Sends timely, context-aware reminders to keep users on track throughout the day.
- **Interactive Chat-Based Control** — Provides a conversational interface for managing, updating, and querying tasks in real time.

---

## Tech Stack

**Frontend**
- React.js
- Tailwind CSS *(optional)*

**Backend**
- Node.js
- Express.js

**AI and Processing**
- OpenAI API — task understanding and natural language processing
- Whisper API — speech-to-text conversion

**Database**
- MongoDB

---

## Architecture

The following diagram outlines the core data flow within Secrexa:

```
User Input
    |
    v
Speech-to-Text (Whisper API)
    |
    v
Backend (Node.js / Express.js)
    |
    v
AI Processing (OpenAI API)
    |
    v
Task Structuring
    |
    v
Database (MongoDB)
    |
    v
Frontend (React.js)
```

---

## Installation

**Prerequisites:** Node.js and npm must be installed on your system.

**1. Clone the repository**
```bash
git clone https://github.com/your-username/secrexa.git
```

**2. Navigate into the project directory**
```bash
cd secrexa
```

**3. Install dependencies**
```bash
npm install
```

**4. Start the development server**
```bash
npm run dev
```

---

## Environment Variables

Create a `.env` file in the root directory and configure the following variables:

```env
OPENAI_API_KEY=your_openai_api_key
MONGODB_URI=your_mongodb_connection_string
PORT=your_preferred_port
```

---

## Future Improvements

- **Mobile Application** — A cross-platform mobile app built with React Native.
- **Personalized AI Behavior** — Adaptive responses and task handling tailored to individual user patterns.
- **Mood-Based Recommendations** — Context-aware suggestions based on user tone and activity history.
- **Analytics Dashboard** — Visual insights into task completion rates, productivity trends, and usage patterns.
- **Third-Party Integrations** — Seamless connectivity with Google Calendar and Notion.

---

## Vision

Secrexa is built on the belief that managing daily tasks should require no effort at all. By combining conversational AI with smart scheduling, Secrexa aims to become a reliable digital companion that understands your needs, anticipates your schedule, and keeps your life organized — so you can focus on what actually matters.

---

## Contributing

Contributions are welcome. To get started:

1. Fork the repository.
2. Create a new branch for your feature or fix: `git checkout -b feature/your-feature-name`
3. Commit your changes with a clear message: `git commit -m "Add: your feature description"`
4. Push to your fork: `git push origin feature/your-feature-name`
5. Open a Pull Request and describe your changes.

Please ensure your code follows the existing style and that all changes are well-documented.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Author

**Name:** Your Name  
**GitHub:** [github.com/your-username](https://github.com/your-username)  
**LinkedIn:** [linkedin.com/in/your-profile](https://linkedin.com/in/your-profile)