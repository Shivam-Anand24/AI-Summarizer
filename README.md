# Summarize Articles with OpenAI GPT-4 App

![Summarize Articles with OpenAI GPT-4](![image](https://github.com/Shivam-Anand24/Article-Summarizer-using-ChatGPT4-API/assets/97556177/c33be75a-2af2-45ca-b0c7-a777b3dca628)
)

Welcome to the **Summarize Articles with OpenAI GPT-4** app! This application utilizes the power of OpenAI's GPT-4 language model to generate concise summaries of articles from the web. With just a simple link to an article, users can obtain a one-paragraph long summary, making it easy to grasp the main ideas without reading the entire content.

## Features

- **Effortless Summarization**: Users can quickly summarize lengthy articles by inputting the article's URL into the app.
- **GPT-4 Language Model**: The app leverages OpenAI's GPT-4, a state-of-the-art language model, to generate coherent and contextually accurate summaries.
- **Sleek UI with Tailwind CSS**: The app boasts a clean and modern user interface designed using the Tailwind CSS framework, ensuring a pleasant user experience.
- **Global State Management with Redux**: Redux is employed to manage the app's global state, providing seamless interactions and data management.
- **Fast Development with Vite**: The Vite build tool is used for its speed and efficiency in the development process, allowing for a smooth and productive workflow.
- **Integration with RapidAPI**: The app integrates with the RapidAPI platform to access the OpenAI GPT-4 API, enabling powerful article summarization capabilities.
- **Deployed on Netlify**: The app is deployed on Netlify, providing a reliable and accessible platform for users to interact with the summarization functionality. You can access the deployed app [here](https://majestic-puppy-250aa0.netlify.app/).

## How to Use

1. Visit the deployed app at [https://majestic-puppy-250aa0.netlify.app/](https://majestic-puppy-250aa0.netlify.app/).
2. On the app's homepage, you'll find a text input field where you can paste the URL of the article you want to summarize.
3. After pasting the URL, click the "Summarize" button.
4. The app will send the article's URL to the OpenAI GPT-4 API via RapidAPI and retrieve a one-paragraph summary.
5. The generated summary will be displayed on the screen, allowing you to quickly grasp the main points of the article.

## Installation and Development

To set up the development environment and run the app locally, follow these steps:

1. Clone this GitHub repository:

   ```bash
   git clone https://github.com/your-username/summarize-articles-gpt4.git
   ```

2. Navigate to the project directory:

   ```bash
   cd summarize-articles-gpt4
   ```

3. Install the dependencies using npm or yarn:

   ```bash
   npm install
   # or
   yarn install
   ```

4. Create a `.env` file in the project root and add your RapidAPI key:

   ```env
   VITE_RAPIDAPI_KEY=your_rapidapi_key_here
   ```

5. Start the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

6. Open your browser and visit `http://localhost:3000` to interact with the app in your local environment.

## Credits

- Built by [Your Name]
- OpenAI GPT-4 API integration using [RapidAPI](https://rapidapi.com/)
- UI design with [Tailwind CSS](https://tailwindcss.com/)
- Developed with [Vite](https://vitejs.dev/)
- State management powered by [Redux](https://redux.js.org/)
- Deployed on [Netlify](https://www.netlify.com/)


---

Thank you for using the Summarize Articles with OpenAI GPT-4 app! If you have any questions or feedback, please feel free to create an issue in the GitHub repository.
