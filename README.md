# College AI Assistant (Feature Set C)

A lightweight, purely front-end college chatbot assistant designed to answer everyday student queries about admissions, courses, exams, fees, timetable, attendance, assignments, results, internships, and facilities.

## Features

- **Keyless AI Integration**: Uses Pollinations AI (`text.pollinations.ai`) as a free, open-source-friendly API endpoint for dynamic text generation. No API keys, authentication, or setup is required.
- **Local Knowledge Base (KB)**: Comes pre-configured with a local knowledge base (a list of common college questions and answers). This data acts as the context for the AI, ensuring accurate and policy-specific answers.
- **Zero Backend Required**: Built entirely with HTML, CSS, and Vanilla JavaScript. Everything runs in the browser, making it trivial to deploy.
- **Conversation History**: Saves your chat history securely in your browser's local storage so you don't lose your previous questions.
- **Responsive Design**: Designed with modern UI/UX principles, glassmorphism, smooth animations, and optimized for both desktop and mobile viewing.
- **FAQ Section**: Searchable frequently asked questions with category filters.

## How to Deploy

Because this project uses no back-end and requires no API keys, deploying it is as simple as hosting a static HTML file.

1. **GitHub Pages**:
   - Push this repository to GitHub.
   - Go to the repository **Settings** > **Pages**.
   - Select the `main` branch as the source and hit Save.
   - Your chatbot will be live!

2. **Vercel / Netlify**:
   - Create a new project in Vercel or Netlify.
   - Import this Git repository.
   - Deploy without any build commands.

## Local Development

To modify or run the project locally:
1. Clone the repository to your local machine.
2. Double-click on `index.html` to open it in your browser.
3. To update the college's data, simply edit the `KB` array inside `index.html`. The AI will automatically adapt to the new information.

## Tech Stack
- HTML5
- CSS3 (Vanilla)
- JavaScript (ES6+)
- [Pollinations AI](https://pollinations.ai/) (for free LLM text generation)
