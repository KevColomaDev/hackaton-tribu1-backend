# FastApi example Project

A brief description of your project.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [License](#license)

## Requirements

- Python 3.12.3
- An OpenAI Api Key
- **Important:** Create an `.env` file based on the `.env.template` file and fill in the necessary values.


## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/devmatchworking/hackaton-tribu1-backend.git
    ```

2. Create a virtual environment:

    ```bash
    virtualenv -p python3.12.3  env
    ```

3. Activate the virtual environment:

    ```bash
    .\env\Scripts\activate
    ```

4. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Start the FastAPI server:

    ```bash
    python api/main.py
    ```

2. Open your browser and navigate to `http://localhost:8000` to access the API.

## API Documentation

The API documentation can be found at `http://localhost:8000/docs`.