# Health care ADR recommendation

## Overview

The Health Care ADR Recommendation project aims to provide recommendations for adverse drug reactions (ADRs) using various data processing and machine learning techniques. The project leverages optical character recognition (OCR) for data extraction, natural language processing (NLP) for context understanding, and integrates with external APIs to enhance its capabilities.&#8203;:contentReference[oaicite:2]{index=2}

## Features

- **Optical Character Recognition (OCR):** :contentReference[oaicite:3]{index=3}&#8203;:contentReference[oaicite:4]{index=4}

- **Natural Language Processing (NLP):** :contentReference[oaicite:5]{index=5}&#8203;:contentReference[oaicite:6]{index=6}

- **Data Preprocessing:** :contentReference[oaicite:7]{index=7}&#8203;:contentReference[oaicite:8]{index=8}

- **API Integrations:**
  - **Google Knowledge Graph API:** :contentReference[oaicite:9]{index=9}&#8203;:contentReference[oaicite:10]{index=10}
  - **FoodData Central API:** :contentReference[oaicite:11]{index=11}&#8203;:contentReference[oaicite:12]{index=12}

- **Context Management:** :contentReference[oaicite:13]{index=13}&#8203;:contentReference[oaicite:14]{index=14}

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/KartikAhluwalia/hacknite_project.git
2. Navigate to Project Directory
   ```bash
   cd hacknite_project
3. Install Dependencies: It's recommended to use a virtual environment to manage dependencies.

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   pip install -r requirements.txt

## Usage

After installing the necessary dependencies, you can utilize the various modules as needed. For example, to perform OCR on an image:
    ```bash
    python paddle_ocr.py path/to/image.jpg

Similarly, other scripts can be executed to preprocess data, interact with APIs, and generate ADR recommendations. Ensure that you have the appropriate API keys and access credentials for the external services used in this project.
