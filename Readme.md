# 🌟 Gemini Chat Assistant

Gemini Chat Assistant is an interactive chat-based application that allows users to engage in conversations, get suggestions, and receive automated responses. The app provides users with a smooth chat experience, complete with light/dark mode toggling, message saving, and local storage support for chat history.

## 📋 Table of Contents

- ✨ Features
- 🛠️ Technologies Used
- 📦 Setup Instructions
- 🚀 Usage


## ✨ Features

- **💬 Interactive Chat UI:** The app supports chatting with suggested prompts for easy access.
- **🌗 Dark Mode/Light Mode Toggle:** Users can switch between light and dark themes.
- **💾 Message Storage:** Chat history is saved to `localStorage` for persistence.
- **⌨️ Typing Effect:** Displays messages with a smooth typing effect for better user experience.
- **🔗 API Integration:** Generates responses using an API.
- **📋 Message Copying:** Users can copy chat messages with a single click.

## 🛠️ Technologies Used

- **🌐 HTML5**: Structure of the application.
- **🎨 CSS3**: Styling the application, including dark and light mode.
- **⚙️ JavaScript (ES6)**: Interactivity, DOM manipulation, and API requests.
- **🔤 Google Fonts**: Material symbols for icons.
- **🤖 Google Generative Language API**: Fetches responses to user messages.

## 📦 Setup Instructions

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/gemini-chat-assistant.git
    cd gemini-chat-assistant
    ```

2. Open the project in your preferred code editor.

3. Make sure you have a valid API key from Google Cloud for the Generative Language API. Add it to your `script.js` file:

    ```javascript
    const API_KEY = "your-google-api-key";
    ```

4. Run the project by opening the `index.html` file in your browser.

## 🚀 Usage

1. Upon loading the app, the user is greeted with a welcome message and default suggestions for easy access.
2. You can click any suggested prompt to generate a response or type a custom prompt into the input box.
3. The app communicates with the Google Generative Language API and provides a response with a typing effect.
4. Toggle between light and dark mode using the theme button.
5. Clear the chat history by clicking the delete button.
