# One Day, One Project: Machine Learning Challenges

Welcome to my "One Day, One Project" repository! The goal of this repository is to tackle one machine learning project each day. This journey will help me practice and enhance my skills in machine learning and data science.

## Table of Contents

- [Introduction](#introduction)
- [Projects](#projects)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This repository contains a collection of daily machine learning projects. Each day, I will work on a new project, starting with the iris flower classification on Day 1. The projects will cover various classification, regression, clustering, and other machine learning tasks.

## Projects

| Day | Project Title                     | Description                                                                                                                                                    |
|-----|-----------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1   | Iris Flower Classification        | The Iris dataset by Fisher (1936) is a classic 150-instance tabular dataset with 4 features, used for classification of three iris plant classes.              |
| 2   | Titanic Survival Prediction       | The Titanic dataset by Frank & Thomas contains information about the survival status of Titanic passengers, with variables such as passenger class, age, gender, and ticket, which have been updated and corrected using primary sources like the Encyclopedia Titanica.                          |
| 3   | House Price Prediction                  | The real estate valuation dataset is a regression problem based on historical market data collected from Sindian District, New Taipei City, Taiwan. It consists of 414 instances and six features, including transaction date, house age, distance to the nearest MRT station, number of convenience stores, latitude, and longitude. The target variable represents house price per unit area in 10,000 New Taiwan Dollars per Ping (1 Ping = 3.3 m²). The dataset contains no missing values and has been randomly split into a training set (2/3) and a testing set (1/3). It was used in a study published in *Applied Soft Computing* to build valuation models using a case-based reasoning approach.                          |
| 4 | Spam Email Detection                               | The SMS Spam Collection is a public dataset for mobile spam research, containing 5,574 labeled SMS messages. It includes 425 spam messages from Grumbletext, a UK spam-reporting forum, and 3,375 ham messages from the NUS SMS Corpus. Stored in a single text file, each line has a label ("ham" or "spam") and the message. The dataset, compiled with manual effort, is widely used for spam detection research.                                                          |
|  5  |   Basic Image Classification                                            |  The dataset made by me (@askewai) appears to involve images that are categorized into two groups: one with glass and one without glass. This suggests a binary classification task where the model is trained to distinguish between these two categories.                                                 |
|  6    |   Student Performance Prediction           | The dataset, compiled by Prof. Jiten Hazarika, includes 666 candidates who qualified for the medical entrance examination in Assam for a specific year. It features 11 variables related to demographics and education, such as gender, caste, coaching, and academic performance in Class X and XII, all of which are crucial for classification tasks in computer science. With no missing values, this multivariate dataset serves as a valuable resource for analyzing factors influencing candidates' success in medical admissions.        |
| 7  | Weather Forecasting    | The dataset, titled "Local Weather Archive," contains historical weather data for Raleigh Durham International Airport, sourced from the NOAA Climate Data Online web service. It has been converted to commonly used units and serves as an archive, meaning it is no longer being updated. Published by the National Oceanic and Atmospheric Administration (NOAA) - National Centers for Environmental Information (NCEI), the dataset was last modified on February 14, 2016, and is publicly accessible under the CC0 1.0 Universal license. It falls under the "Environment" category and is available in English. Metadata was created on November 12, 2020, and last updated on October 19, 2024. |
|  8  |  Heart Disease Prediction   |  The heart disease dataset, includes data from four databases: Cleveland, Hungary, Switzerland, and the VA Long Beach. It is a multivariate dataset with 303 instances and 13 features, focusing on health and medicine, and is primarily used for classification tasks. The dataset contains 76 attributes, but only 14 are commonly used, with the Cleveland database being the most referenced. The "goal" field indicates the presence of heart disease, ranging from 0 (no presence) to 4. Patient identifiers were replaced with dummy values for privacy. The dataset includes missing values and has been used in research, such as a 1989 study published in the *American Journal of Cardiology*. It features variables like age, sex, blood pressure, cholesterol levels, and heart rate, with no missing values in the listed features.   |
|  ...   |  ...   |  ...  |

Projects will be grouped into basic and intermediate levels which contain google colab (Python) files.

## Installation

To run the projects locally, follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/one-day-one-project.git
    ```

2. Navigate to the project directory:
    ```bash
    cd one-day-one-project
    ```

3. Create a virtual environment:
    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:
      ```bash
      venv\Scripts\activate
      ```
    - On macOS and Linux:
      ```bash
      source venv/bin/activate
      ```

5. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Each project will have its own set of instructions. Navigate to the project's folder and follow the instructions in the project's README file.

For example, to run the Day 1 project:

1. Navigate to the Day 1 project directory:
    ```bash
    cd projects/day-1-iris-flower-classification
    ```

2. Follow the instructions in the `README.md` file within that directory.

## Contributing

Contributions are welcome! If you have suggestions for new projects, improvements, or bug fixes, please open an issue or submit a pull request.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contact

If you have any questions or suggestions, feel free to reach out to me at mayesqprm@gmail.com (mailto:mayesqprm@gmail.com).

Happy coding!
