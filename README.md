# Image Background Remover

A simple, client-side web application that allows users to upload an image and automatically remove its background using the **remove.bg API**.

## 🚀 Features

* **Easy Image Upload:** Upload an image directly from your device.
* **Automatic Background Removal:** Uses a powerful external API to process the image.
* **Before and After Preview:** See a small preview of the original image alongside the background-removed version.
* **Download:** Easily download the resulting transparent image (PNG).

## 🛠️ Technology Stack

* **HTML:** Structure of the web page.
* **CSS:** Styling for a clean, user-friendly interface.
* **JavaScript (Vanilla JS):** Handles file reading, user interaction, and API calls.
* **remove.bg API:** The core service used for background removal.

## ⚙️ Setup and Installation

### Prerequisites

You need a valid **API Key** from `remove.bg` to make the background removal functionality work.

### Local Setup

1.  **Clone the repository** (or download the zip and extract the contents):
    ```bash
    git clone [YOUR_REPOSITORY_URL]
    cd Image-Background-Remover-main
    ```
2.  **Update the API Key:**
    The API key is hardcoded in the `script.js` file. You need to replace the placeholder key with your actual key from remove.bg.

    In `script.js`:
    ```javascript
    const API_KEY = "MKcutZL9EBkjFmhEEtjkggqP"; // <-- REPLACE THIS
    ```

3.  **Open the Application:**
    Simply open the `index.html` file in your web browser. Since all the logic is on the client-side (HTML/CSS/JS), no web server is strictly required for basic functionality.

## 💡 Usage

1.  **Upload Image:** On the start screen, click the "Upload Image" button and select an image file (JPG or PNG).
2.  **View Preview:** The image will be displayed on the screen.
3.  **Remove Background:** Click the "**Remove Background**" button. This will send the image to the `remove.bg` API.
4.  **Download Result:** Once processing is complete, a "Download" button will appear. Click it to save the transparent image to your device.

---

*This README is a reconstruction based on the provided project files (`index.html`, `script.js`, and `style.css`).*
