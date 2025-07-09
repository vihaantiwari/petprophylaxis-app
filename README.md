# petprophylaxis-app
An AI-powered web application for analyzing animal skin symptoms.
# PetProphylaxis

An AI-powered web application designed to assist pet owners in identifying potential skin conditions (burns, marks, symptoms) on their animals. Users can upload an image, and the application will provide insights on possible diseases, general precautions, and potential cures/treatments using the Google Gemini API.

**Disclaimer:** This application provides AI-generated information based on image analysis and **should not replace professional veterinary advice.** Always consult a qualified veterinarian for accurate diagnosis and treatment plans for your pets.

## Features

* Upload images of animal symptoms.
* AI-powered analysis for potential diseases/conditions.
* Information on precautions and cures/treatments.
* Responsive design for various devices.

## How to Use

1.  **Clone or Download this Repository:**
    ```bash
    git clone [https://github.com/YOUR_GITHUB_USERNAME/petprophylaxis-app.git](https://github.com/YOUR_GITHUB_USERNAME/petprophylaxis-app.git)
    # OR download the ZIP file from the GitHub repository page
    ```
2.  **Obtain a Google Gemini API Key:**
    * This application uses the Google Gemini API for image analysis. You will need your own API key.
    * Visit [Google AI Studio](https://aistudio.google.com/) and sign in with your Google account.
    * Follow the instructions to generate a new API key. A free tier is available.
    * **Important:** Keep your API key secure and do not share it publicly in production applications. For this client-side demo, it will be embedded directly.
3.  **Insert Your API Key:**
    * Open the `index.html` file in a text editor.
    * Locate the JavaScript section (within `<script type="module">`).
    * Find the line `const apiKey = "";`
    * Replace the empty quotes `""` with your actual Gemini API key:
        ```javascript
        const apiKey = "YOUR_GENERATED_API_KEY_HERE"; // Replace with your key
        ```
4.  **Open the Application:**
    * Simply open the `index.html` file in your web browser.

## Development

This project is a single HTML file with embedded CSS (Tailwind CSS CDN) and JavaScript.

## License

This project is open-source and available under the [MIT License](LICENSE).
