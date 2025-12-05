# API-Integration-hacktiv8
courses 4 sessions

.env : This file holds environment variables, especially sensitive credentials like your Gemini API key

package.json : Defines dependencies and scripts for the Node.js app

index.js : Contains all the logic for the REST endpoints that interact with Gemini AI. It Sets up an Express app; Connects to Gemini 2.5 Flash model●Defines endpoints to accept text, image, document, and audio inputs; Handles request parsing, file uploads, error management, and responses.

This code block sets up the basic environment for your Gemini AI API server:
●Loads environment variables from .env (for the API key).
●Imports essential libraries for server creation (express), file uploads (multer), file handling (fs/promises), and Gemini AI integration (@google/genai).
●Initializes the Express app and sets up Multer to store uploaded files in the uploads/ folder.
● Creates a Gemini AI client using your API key, and sets the model to "gemini-2.5-flash" (the latest, cost-efficient model).
● Configures Express to accept JSON requests.
● Starts the server on port 3000.
