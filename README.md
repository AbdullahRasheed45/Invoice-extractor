# Invoice Extractor

The **Invoice Extractor** is a Streamlit-based application that leverages Google's Generative AI models to analyze and extract information from invoice images. This application uses a text prompt and an uploaded invoice image to provide detailed responses based on the content of the invoice.

## Features
- **Invoice Analysis**: Upload an invoice image, and the app provides answers to questions based on the content of the invoice.
- **Streamlit Interface**: A simple, interactive UI for input prompts and file uploads.
- **Google Generative AI Integration**: Utilizes Google's Gemini AI model for content generation.
- **Secure API Key Management**: API keys are securely loaded from environment variables.

## How It Works
1. **Input Prompt**: Enter a prompt to describe the task (e.g., "Extract the invoice details").
2. **Upload Invoice**: Upload an image of the invoice in `.jpg`, `.jpeg`, or `.png` format.
3. **Generate Response**: The app sends the prompt and image to the Google Generative AI model and displays the response.

## Requirements

### Python Libraries
The following libraries are required:
- `streamlit`
- `Pillow`
- `google-generative-ai`
- `python-dotenv`

