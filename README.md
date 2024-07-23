# NLP based Spam Mail Detection

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Twitter][twitter-shield]][twitter-url]

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Ruban2205/spam-mail-detection-nlp.svg?style=for-the-badge
[contributors-url]: https://github.com/Ruban2205/spam-mail-detection-nlp/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Ruban2205/spam-mail-detection-nlp.svg?style=for-the-badge
[forks-url]: https://github.com/Ruban2205/Iris_Classification/network/members
[stars-shield]: https://img.shields.io/github/stars/Ruban2205/spam-mail-detection-nlp.svg?style=for-the-badge
[stars-url]: https://github.com/Ruban2205/spam-mail-detection-nlp/stargazers
[issues-shield]: https://img.shields.io/github/issues/Ruban2205/spam-mail-detection-nlp.svg?style=for-the-badge
[issues-url]: https://github.com/Ruban2205/spam-mail-detection-nlp/issues
[license-shield]: https://img.shields.io/github/license/Ruban2205/spam-mail-detection-nlp.svg?style=for-the-badge
[license-url]: https://github.com/Ruban2205/spam-mail-detection-nlp/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/ruban-gino-singh
[twitter-shield]: https://img.shields.io/badge/X.com%20(Twitter)%20-black.svg?style=for-the-badge&logo=X&colorB=555
[twitter-url]: https://x.com/Rubangino

# Spam Mail Detection Using NLP

This repository contains the code and resources for a Spam Mail Detection project using Natural Language Processing (NLP) techniques. The project aims to classify emails as spam or non-spam based on their content.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Datasets](#datasets)
- [Model](#model)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Spam email is a significant issue that affects email users globally. This project leverages NLP techniques to develop a robust model that can effectively detect spam emails, thereby improving email security and user experience.

## Features

- Data preprocessing and cleaning
- Feature extraction using techniques such as TF-IDF
- Machine learning model training and evaluation
- Model deployment for real-time spam detection

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/Ruban2205/spam-mail-detection-nlp.git
    cd spam-mail-detection-nlp
    ```

2. Create a virtual environment:
    ```sh
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

To run the program, write the following command:
```sh
python main.py
```

## Datasets

The dataset used in this project can be found in the `data/` directory. It includes both raw and processed email data. The raw data is preprocessed and split into training and testing sets for model training and evaluation. 

**Dataset Link**: [https://www.kaggle.com/datasets/venky73/spam-mails-dataset/data](https://www.kaggle.com/datasets/venky73/spam-mails-dataset/data)

## Model

This project employs machine learning algorithms such as Logistic regression and Random Forest. Feature extraction is done using TF-IDF, and the models are evaluated based on accuracy, precision, recall, and F1-score. 

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes. Ensure your code adheres to the existing style and include relevant tests. 

## License 

This project is licensed under the MIT License. See the [LICENSE](/LICENSE) file for more details. 

## Contact 

For any questions or feedback, please contact: 

**Ruban Gino Singh**
Email: [comment@rubangino.in](https://mailto:comment@rubangino.in/)
Website: [www.rubangino.in](https://rubangino.in/)
