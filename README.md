# Recipe Recommendation System

## Introduction

The Recipe Recommendation System is a Python-based project that helps users find recipes based on the ingredients they have available. This system provides recipe suggestions by comparing user-supplied ingredients with a dataset of recipes, taking into account the ingredient differences.

## Table of Contents

- [Project Overview](#recipe-recommendation-system)
- [Introduction](#introduction)
- [Table of Contents](#table-of-contents)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Data Preprocessing](#data-preprocessing)
- [Recipe Recommendation](#recipe-recommendation)
- [Contributing](#contributing)
- [License](#license)

## Features

- Allows users to input a list of ingredients they have at home.
- Recommends recipes based on ingredient availability.
- Sorts recipes by ingredient difference (fewer missing ingredients, higher recommendation).
- Utilizes a dataset of recipes for recommendations.

## Requirements

- Python 3.x
- Pandas
- TextBlob
- NLTK
- String

You can install the required Python packages using `pip`:

```bash
pip install pandas textblob nltk string regex
```

## Installation

1) Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/recipe-recommendation-system.git
```

2) Navigate to the project directory:

```bash
cd recipe-recommendation-system
```

3) Install the required packages (as mentioned in the Requirements section) using pip.


## Usage

### Data Preprocessing

Before using the Recipe Recommendation System, you need to preprocess your dataset of recipes. You can follow these steps:

1) Load your dataset into the system.
2) Clean the dataset by removing non-English recipes or columns containing Hindi.
3) Preprocess the ingredients column into a standardized format (ingredient: quantity).

## Recipe Recommendation System

1) Run the script.
2) Enter the ingredients you have available, separated by commas.
3) The system will recommend recipes based on your input and sort them by ingredient difference.
4) You can explore the recommended recipes, their ingredients, and instructions.

## Contributing
Contributions are welcome! If you have any ideas or improvements, please open an issue or submit a pull request.
