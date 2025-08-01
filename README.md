# Quiz App

> 🚀 **Training Project from [roadmap.sh](https://roadmap.sh/projects/quiz-app)**  
> Inspired by [@roadmapsh](https://github.com/roadmapsh) — [Project Link](https://roadmap.sh/projects/quiz-app)

An AI-powered quiz application built with Vite, TailwindCSS, and Toastify. Users can generate multiple-choice quizzes on any topic using the Gemini API, answer questions within a time limit, and view their score with animated feedback.

## Features

- **AI-generated quizzes:** Enter any topic and get a set of multiple-choice questions generated by Gemini.
- **Time-limited questions:** Each question has a countdown timer.
- **Score tracking:** See your score update in real-time and view your final score with a progress circle.
- **Animated UI:** Smooth transitions and feedback using custom CSS animations and Toastify notifications.
- **Responsive design:** Works well on desktop and mobile devices.

## Technologies Used

- [Vite](https://vitejs.dev/) for fast development and build.
- [TailwindCSS](https://tailwindcss.com/) for utility-first styling.
- [Toastify](https://github.com/apvarun/toastify-js) for toast notifications.
- [Gemini API](https://ai.google.dev/) for generating quiz questions.

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- A Gemini API key (set as `VITE_APP_GEMINI_API_KEY` in `.env`)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/quiz-app.git
   cd quiz-app
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

3. Add your Gemini API key to a `.env` file:
   ```
   VITE_APP_GEMINI_API_KEY=your_api_key_here
   ```

### Running the App

Start the development server:

```sh
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Building for Production

```sh
npm run build
```

## Customization

- Change quiz settings (number of questions, timer) in [`src/main.js`](src/main.js).

## License

MIT

---

**Note:** This app uses the Gemini API to generate quiz questions. Make sure to comply with API usage limits and terms.

**Tags:**  
`#roadmapsh` `#quiz-app` `#training-
