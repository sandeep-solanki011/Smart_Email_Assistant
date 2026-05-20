# Smart Email Assistant

## Description
Smart Email Assistant is an AI-powered application that helps users generate professional email replies automatically using AI.

---

## Features

- AI generated email replies
- Professional email response generation
- Easy-to-use interface
- Fast response generation
- Clean UI

---

## Tech Stack

### Frontend
- React.js
- Tailwind CSS

### Backend
- Spring Boot
- Java

### AI
- Gemini API

---

## Screenshots

### Home Page
![Home](screenshots/home.png)

### AI Reply Generation
![Reply](screenshots/reply.png)

### Loading State
![Loading](screenshots/loading.png)

### Gmail Integration
![Gmail](screenshots/gmail-extension.png)

---

## Installation

### Clone Repository

```bash
git clone https://github.com/sandeep-solanki011/Smart_Email_Assistant.git
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd backend
mvn spring-boot:run
```

---

## Environment Variables

Create `.env` file and add:

```env
GEMINI_API_KEY=your_api_key
```

---

## API Endpoint

```http
POST /generate-email
```

---

## Folder Structure

```text
frontend/
backend/
screenshots/
```

---

## Future Improvements

- Multi-language support
- Better AI suggestions
- Authentication system
- Email templates

---

## Author

### Sandeep Solanki

GitHub:
https://github.com/sandeep-solanki011
