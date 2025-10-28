# AI Resume Analyzer

A powerful tool that leverages generative AI to analyze your resume against a specific job description, providing a detailed score and actionable feedback to improve your chances of landing an interview.


## How It Works

This isn't just a simple keyword-matching tool. It uses a sophisticated AI model (Anthropic's Claude 3 Sonnet) to perform a deep, contextual analysis of your resume, much like a human recruiter would.

1.  **Upload:** Provide a job description and upload your resume in PDF format.
2.  **Analyze:** The application sends your resume and the job description to the AI for a comprehensive review.
3.  **Score & Feedback:** You receive a detailed breakdown of your resume's strengths and weaknesses across several categories, including:
    *   **ATS Score:** How well your resume is optimized for Applicant Tracking Systems.
    *   **Content:** Relevance and quality of the content.
    *   **Structure:** Layout and organization.
    *   **Tone & Style:** Professionalism and language.

The entire application runs in your browser, using [Puter.com](https://puter.com) as a serverless backend for authentication, file storage, and AI processing.

## Features

- **AI-Powered Analysis:** Get expert-level feedback without the expert.
- **Direct Job Description Matching:** Tailor your resume for the exact job you're applying for.
- **Detailed Scoring:** Understand your resume's performance at a glance with scores for multiple categories.
- **Actionable Suggestions:** Receive concrete tips on how to improve each section of your resume.
- **Serverless Architecture:** All data (resumes, analysis results) is stored securely in your personal Puter account.
- **Modern Tech Stack:** Built with React, Vite, and Tailwind CSS for a fast and responsive experience.

## Tech Stack

- **Frontend:** React, Vite, TypeScript, Tailwind CSS
- **Backend & AI:** [Puter.js](https://puter.com)
  - Authentication
  - File Storage (for resumes)
  - Key-Value Store (for analysis data)
  - AI Chat (Claude 3 Sonnet)

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later recommended)
- [npm](https://www.npmjs.com/), [yarn](https://yarnpkg.com/), or [pnpm](https://pnpm.io/)

### Installation

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/gubbysbyte/AI-Powered-Application-Tracker.git
    cd ai-resume-analyzer
    ```

2.  **Install dependencies:**
    ```sh
    npm install
    ```
    *(or `yarn install`, `pnpm install`)*

3.  **Run the development server:**
    ```sh
    npm run dev
    ```

4.  **Open the application:**
    Open your browser and navigate to `http://localhost:5173` (or the address provided by Vite).

5.  **Sign In:**
    The application uses Puter for authentication. You will be prompted to sign in or create a free Puter.com account. This account will be your personal cloud storage for this and other Puter-compatible apps.

## License

This project is licensed under the MIT License - see the LICENSE file for details.