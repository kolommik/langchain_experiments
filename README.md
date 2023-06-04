# Langchain Experiments Repository

This repository contains Jupyter notebooks for lessons from the [Langchain course](https://learn.deeplearning.ai/langchain).

## Installation

Before running any code, ensure you have the following requirements:

- Python (3.10 or newer)
- - [Poetry](https://python-poetry.org/) for package management
- An OpenAI API key

### Setup

1. Clone the repository:

```bash
git clone https://github.com/kolommik/langchain_experiments.git
```

2. Navigate to the project directory:

```bash
cd langchain_experiments
```

3. Install dependencies using Poetry:

```bash
poetry install
```

4. Activate the virtual environment:

```bash
poetry shell
```

## Environment Variables

This project uses environment variables for configuration.

To set them up:

1. Copy the `.env.sample` file in the root directory and rename it to `.env`.
2. Add your OpenAI API key to the `.env` file.

Your `.env` file should look like this:

```env
OPENAI_API_KEY=your_openai_api_key_here
```

Please make sure not to commit the `.env` file to the repository.

## Project Structure

The repository is structured as follows:

- `/Notebooks`: This directory contains Jupyter notebooks corresponding to the lessons from the course.

## Usage

To run any notebook, navigate to the `/Notebooks` directory and open the notebook using Jupyter:

```bash
cd Notebooks
jupyter notebook notebook_name.ipynb
```

Replace "notebook_name.ipynb" with the name of the notebook you want to run.

## Contributing

This is a private repository, mainly for personal learning and testing. Therefore, contributions are not currently accepted.
