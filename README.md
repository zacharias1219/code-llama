# code-llama

## Summary

We use CodeLlama, a state-of-the-art large language model for coding, to build a personal code assistant. This assistant aims to help users write code efficiently by providing code snippets and solutions based on custom prompts.
We create a user-friendly interface for the code assistant using Gradio.
We use the model file to specify the behaviour of the Ollama model.
Then we create an interface which takes in request/prompts and gives outputs.

## Usage

To use the code assistant, follow these steps:

1. Install the Ollama model by running the following command in the terminal:

    ```shell
    ollama create codr -f Modelfile
    ```

2. Run the code assistant by executing the following command:

    ```shell
    ollama run codr
    ```

3. Start the Gradio interface by running the following command:

    ```shell
    python app.py
    ```

4. Access the code assistant through the user-friendly interface and provide your prompts to get code snippets and solutions.
