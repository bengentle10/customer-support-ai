# Customer-Support-AI

## Overview
​<light>Customer-Support-AI is a Next.js application built to enhance customer support for businesses in the food and nutrition sectors.</light>​ By leveraging Pinecone for Retrieval-Augmented Generation (RAG) and fetching reliable information from [Healthline](https://www.healthline.com/nutrition), this tool provides accurate and contextual answers to health-related queries. This project aims to empower customer support teams by offering quick and relevant responses to their customers' inquiries.

## Motivation
In an increasingly digital world, customers expect prompt and accurate responses. By utilizing AI to assist support teams, this project seeks to improve response times and enhance customer satisfaction. The integration of health-related content helps ensure the accuracy of information provided to customers.

## Tech Stack
This project is built using the following technologies:
- **Next.js**: A React framework for building server-rendered applications.
- **JavaScript**: The programming language employed to develop the application.
- **Pinecone**: A vector database service used for semantic searching of the health-related content.
- **AWS SDK**: For integrating with AWS Bedrock to use generative AI models.
- **Google Generative AI**: For generating contextual responses to user prompts.
- **Axios**: For making HTTP requests to fetch external content.
- **Cheerio**: For parsing and manipulating the HTML of fetched web pages.

## Installation
To set up this project locally, follow the steps below:

### Prerequisites
- Node.js and npm (Node Package Manager) installed on your machine.
- Access to AWS and Google Cloud services for API keys.

### Steps
1. Clone the repository:
bash
   git clone https://github.com/bengentle10/customer-support-ai.git

2. Navigate into the project directory:
bash
   cd Customer-Support-AI

3. Install the dependencies:
bash
   npm install

4. Set up environment variables in a `.env.local` file:

env
   AWS_REGION=your_aws_region
   AWS_ACCESS_KEY_ID=your_access_key_id
   AWS_SECRET_ACCESS_KEY=your_secret_access_key
   GOOGLE_GEMINI_API_KEY=your_google_gemini_api_key
   PINECONE_API_KEY=your_pinecone_api_key

## Usage
To start the application, run the following command:

bash
npm run dev

Open your browser and navigate to `http://localhost:3000`. You will be greeted by the AI assistant, ready to answer your questions about nutrition and related topics.

### Example Interaction
1. Type your question regarding food or nutrition into the input box.
2. Select the provider (Google Gemini or AWS Bedrock) and press "Send".
3. The assistant will respond with relevant information fetched from Healthline or generated content.

## Features
- AI-powered responses to health and nutrition queries.
- Contextual understanding via embeddings processed with Pinecone.
- Integration with two AI providers: Google Gemini and AWS Bedrock for enhanced response generation.

## Contributing
Contributions are welcome! If you would like to contribute to this project, please follow these steps:
1. Fork the repository.

2. Create your feature branch:
bash
   git checkout -b feature/YourFeature

3. Commit your changes:
bash
   git commit -m "Add your message"

4. Push to the branch:
bash
   git push origin feature/YourFeature
5. Open a pull request.


## Contact
For any inquiries or support, you can reach me at bengentle10@gmail.com
