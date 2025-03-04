# Data Engineering Systems Course - Week 2
Welcome to the repository for the second week of the Data Engineering Systems course at Duke University.
[![CI](https://github.com/nogibjj/monasaeed-week2/actions/workflows/cicd.yml/badge.svg)](https://github.com/nogibjj/monasaeed-week2/actions/workflows/cicd.yml)

## Project Overview
This project leverages a template developed last week [mts79-week1](https://github.com/nogibjj/mts79-week1), which includes essential tools and configurations to streamline the development process.

Additionally, this project utilizes the **Diamond Dataset** to perform descriptive statistics using **Pandas**. It generates a comprehensive summary report, offering insights into the dataset's key attributes and statistical measures.

## Contents

- **.devcontainer**: Configuration for a consistent development environment.
- **Makefile**: Automation of common tasks and commands.
- **.github**: GitHub Actions for continuous integration and deployment.
- **requirements.txt**: List of dependencies required for the project.
- **diamonds_summary.md**: a file that contains summary statistics of the diamonds dataset, it also contains a visualization of the distribution of diamonds prices.
> For a more comprehensive analysis of the dataset check my other repository [diamonds_dataset_analysis](https://github.com/monatagelsir7/diamonds_dataset_analysis)

## Getting Started
1. **Clone the repository:**

    ```bash
    git clone https://github.com/nogibjj/monasaeed-week2.git
    ```

2. **Navigate into the project directory:**

    ```bash
    cd monasaeed-week2
    ```

3. **Install the required dependencies:**

    You can find the list of required packages in the `requirements.txt` file. Run the following command to install them:

    ```bash
    pip install -r requirements.txt
    ```
4. **Run the script:**

    ```bash
    python main.py
    python test_main.py
    ```



