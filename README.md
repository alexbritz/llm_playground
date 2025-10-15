# llm_playground

A simple playground to experiment with LLMs using your personal OpenAI API key.  
See what ChatGPT does in the background.

## Setup Instructions

1. **Create an OpenAI API Key**  
    Sign up at [OpenAI](https://platform.openai.com/account/api-keys) and generate an API key.

2. **Save the API Key in `.env`**  
    Create a `.env` file in the project root and add your API key. You can also use the `.env` template:
    ```
    OPENAI_API_KEY=your_api_key_here
    ```

3. **Create the Conda Environment**
    ```bash
    conda env create -f environment.yml
    ```

4. **Activate the Environment**
    ```bash
    conda activate llm_playground
    ```

5. **Launch Jupyter Notebook**
    ```bash
    jupyter notebook
    ```
    Open the notebook in your browser to explore and test the playground.

## Additional Resources

- [Managing Conda Environments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)