# Notebooks for the Analytics Vidhya course: "Building Agents"

- [Live-training official website from Analytics]()
# Overview

## Setup

**Conda**

- Install [anaconda](https://www.anaconda.com/download)
- Create an environment: `conda create -n vidhya-agents python=3.11`
- Activate your environment with: `conda activate vidhya-agents`
- Install requirements with: `pip install -r requirements.txt` (the `requirements.txt` file is in the `requirements` folder)
- Setup your openai [API key](https://platform.openai.com/)

**Pip**


1. **Create a Virtual Environment:**
    Navigate to your project directory. If using Python 3's built-in `venv`:
    ```bash
    python -m venv vidhya-agents
    ```
    If you're using `virtualenv`:
    ```bash
    virtualenv vidhya-agents
    ```

2. **Activate the Virtual Environment:**
    - **On Windows:**
      ```bash
      .\vidhya-agents\Scripts\activate
      ```
    - **On macOS and Linux:**
      ```bash
      source vidhya-agents/bin/activate
      ```

3. **Install Dependencies from `requirements.txt`:**
    ```bash
    pip install python-dotenv
    pip install -r requirements.txt
    ```

4. Setup your openai [API key](https://platform.openai.com/)

Remember to deactivate the virtual environment once you're done by simply typing:
```bash
deactivate
```

## Setup your .env file

- Change the `.env.example` file to `.env` and add your OpenAI API key.

## To use this Environment with Jupyter Notebooks:

```python3 -m ipykernel install --user --name=vidhya-agents```

## Set up your OAI_CONFIG_LIST file for autogen
- Create a file named: OAI_CONFIG_LIST containing your API keys for OpenAI as demonstrated below:

```
[
    {
        "model": "gpt-4o",
        "api_key": "YOUR API KEY HERE"
    }
]
``` 

## Official Training Website

For more information about the live-training, visit the [official website]().