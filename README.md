# Gemini Code Converter

## Project Purpose
The Gemini Code Converter is a web-based tool designed to facilitate code transformation using the power of Google's Gemini AI. Users can input their original code, define a target pattern or structure, and provide specific AI instructions to guide the conversion process. This tool is ideal for refactoring, migrating code between frameworks, or adapting code to new architectural patterns.

## Features
*   **AI-Powered Code Conversion:** Leverage Google Gemini AI to intelligently convert code.
*   **Flexible Input:** Define original code, target patterns, and AI instructions to achieve desired transformations.
*   **Real-time Conversion:** Get instant results for your code conversion requests.
*   **Clipboard Integration:** Easily copy the converted code to your clipboard.

## Technologies Used
*   **Frontend:** Vue 3
*   **Code Editor:** CodeMirror
*   **AI Integration:** Google Gemini AI (via `@google/genai` SDK)
*   **Build Tool:** Vite

## Setup Instructions

To get this project up and running on your local machine, follow these steps:

### Prerequisites
*   Node.js (LTS version recommended)
*   npm or Yarn

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/ai-code-converter.git
    cd ai-code-converter
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```

### Environment Variables

This project requires a Google Gemini API key.

1.  **Create a `.env` file** in the root of the project:
    ```
    VITE_GEMINI_API_KEY=YOUR_GEMINI_API_KEY
    ```
2.  **Replace `YOUR_GEMINI_API_KEY`** with your actual API key obtained from the Google AI Studio.

### Running the Project

To start the development server:

```bash
npm run dev
# or
yarn dev
```

The application will typically be available at `http://localhost:5173` (or another port if 5173 is in use). Open this URL in your web browser to access the Gemini Code Converter.