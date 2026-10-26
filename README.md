# 🚘 PlateVision AI

**AI-Powered License Plate Detection and Feature Extraction System**

PlateVision AI is a Python-based web application that analyzes vehicle images to detect license plates and recognize their characters using the Plate Recognizer Snapshot API.

## ✨ Features

- **Image Upload:** Upload vehicle images in JPG, JPEG, PNG, or WEBP format.
- **License Plate Detection:** Detect license plates in uploaded images.
- **Character Recognition:** Extract the recognized license plate text.
- **Bounding Box Visualization:** Highlight detected license plate regions in the image.
- **Confidence Scores:** Display plate detection and character recognition confidence scores returned by the API.
- **Recognition Results:** View extracted plate information and the raw API response.
- **Interactive Interface:** Use a simple web interface built with Streamlit.

## 🛠️ Technologies Used

- Python
- Streamlit
- Plate Recognizer Snapshot API
- Requests
- Pillow (PIL)

## ⚙️ How It Works

1. Upload a vehicle image through the application.
2. Enter a valid Plate Recognizer API token.
3. Submit the image for recognition.
4. The API analyzes the image and returns detected license plate information.
5. The application displays the recognized characters, confidence scores, and detected plate location.

## 📋 Requirements

- Python 3.10 or newer
- A Plate Recognizer account and valid API token
- Internet connection
- Required Python libraries listed in `requirements.txt`

## 🚀 Installation and Setup

**1. Clone the repository**

```bash
git clone https://github.com/kkavinaya30-design/license-plate-feature-extraction.git
```

**2. Open the project directory**

```bash
cd license-plate-feature-extraction
```

**3. Install dependencies**

```bash
python -m pip install -r requirements.txt
```

**4. Run the application**

```bash
python -m streamlit run app.py
```

**5. Use the application**

Open the local URL displayed in your terminal, enter your API token in the sidebar, upload a vehicle image, and click **Detect license plate**.

## 🔐 API Security

The application requires a valid Plate Recognizer API token. Enter the token at runtime and never publish it in source code or commit it to GitHub.

API access, usage limits, and availability depend on your Plate Recognizer account.

## 📌 Project Status

This repository contains a Python application integrating with the Plate Recognizer Snapshot API. It is a separate implementation from the original PlateVision AI agent created using AshnaAI.

## 🔮 Future Improvements

- Improve image preprocessing for difficult lighting conditions.
- Add support for displaying recognition history.
- Export recognition results to CSV.
- Explore additional image-processing and feature-extraction methods.

## ⚠️ Disclaimer

Recognition results may be inaccurate depending on image quality, lighting, angle, or obstructions. Use the application responsibly and follow applicable privacy and data-protection requirements.

## 👩‍💻 Author

**Kavinaya Karuppusamy**

GitHub: [kkavinaya30-design](https://github.com/kkavinaya30-design)
