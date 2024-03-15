# Art Style Detector 

![Art Style Detection](https://img.shields.io/badge/Art%20Style%20Detection-blue)
![Python](https://img.shields.io/badge/Made%20with-Python-green)

Welcome to the Art Style Detection project repository! This project focuses on detecting art styles from images using machine learning techniques. We utilize web scraping, preprocessing, and various classification models to achieve accurate classification of art styles.

## Table of Contents
- [Introduction](#introduction)
- [Data Collection](#data-collection)
- [Preprocessing](#preprocessing)
- [Classification Models](#classification-models)
- [About the Data](#about-the-data)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Art style detection involves identifying the artistic style of a given artwork, which can be a challenging task due to the diverse and subjective nature of art. This project aims to automate this process using machine learning algorithms. We scrape images from WikiArt.org, preprocess them, and train classification models to accurately predict the art style of the images.

## Data Collection
We collect images from WikiArt.org using web scraping techniques implemented with BeautifulSoup and Selenium. The images are categorized into three art styles: Cubism, Impressionism, and Surrealism. In total, we scrape around 5000 images for our dataset.

## Preprocessing
Before training our models, we preprocess the images to enhance features and reduce noise. This involves applying filters and color palettes to standardize the appearance of the images across different styles. Preprocessing helps improve the performance of our classification models by making the features more discernible.

## Classification Models
We experiment with two different classification models: Support Vector Machine (SVM) and Convolutional Neural Network (CNN). These models are trained on the preprocessed image data to learn the distinctive features of each art style. We evaluate the performance of each model and select the best-performing model for art style detection.

## About the Data
Our dataset comprises approximately 5000 images categorized into three art styles: Cubism, Impressionism, and Surrealism. Each image is labeled with its corresponding art style, allowing our classification models to learn and differentiate between the styles during training.

## Installation
To set up the environment for running this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/art-style-detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd art-style-detection
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. **Data Preparation**: Ensure that you have the necessary datasets containing images of Cubism, Impressionism, and Surrealism artworks.
2. **Data Scraping**: Use the provided scripts to scrape images from WikiArt.org or prepare your own dataset.
3. **Preprocessing**: Apply filters and color palettes to preprocess the images for better feature extraction.
4. **Model Training**: Train the SVM and CNN models on the preprocessed image data.
5. **Evaluation**: Evaluate the performance of the trained models using validation or test datasets.
6. **Art Style Detection**: Use the trained model to predict the art style of new images.

## Contributing
Contributions to this project are welcomed and appreciated. If you have any suggestions, feature requests, or bug reports, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
