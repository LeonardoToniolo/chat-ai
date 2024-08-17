# Chat AI

This repository is a project that follows a YouTube tutorial on creating a Chatbot using OpenAI's ChatGPT API and the Vercel SDK. The chatbot is designed to handle various conversational scenarios using the latest advancements in AI.

## Overview

This project demonstrates how to integrate OpenAI's ChatGPT with Vercel to build a functional chatbot. The tutorial covers the setup, implementation, and deployment of the chatbot on Vercel, a platform for developing and deploying serverless applications.

## Features

- **Natural Language Processing:** Uses OpenAI's powerful ChatGPT API to understand and generate human-like responses.
- **Deployment on Vercel:** Easily deployable using Vercel's serverless functions.
- **Interactive Chat Interface:** A simple and intuitive interface for users to interact with the chatbot.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js installed on your local machine
- A Vercel account
- OpenAI API key

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/LeonardoToniolo/chat-ai.git
   ```

2. Navigate to the project directory:

   ```bash
   cd chat-ai
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory and add your OpenAI API key:

   ```bash
   OPENAI_API_KEY=your_openai_api_key
   ```

### Usage

To run the chatbot locally:

```bash
npm run dev
```

The chatbot will be accessible at `http://localhost:3000`.

### Deployment

To deploy the chatbot to Vercel:

1. Install the Vercel CLI:

   ```bash
   npm install -g vercel
   ```

2. Link your project to a new or existing Vercel project:

   ```bash
   vercel link
   ```

3. Deploy the chatbot:

   ```bash
   vercel deploy
   ```

Your chatbot will be live and accessible via the Vercel-generated URL.

## Video Tutorial

For a step-by-step guide on how to create this chatbot, refer to the [YouTube video tutorial](https://www.youtube.com/watch?v=CPRx_WVkJ8g).

## Contributing

If you have suggestions for improvements or encounter any issues, feel free to open a pull request or an issue on this repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Let me know if you need any changes or additional details!