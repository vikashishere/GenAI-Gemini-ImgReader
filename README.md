# GenAI-Gemini-InvoiceInterpreter

GenAI-Gemini-InvoiceInterpreter is an AI application powered by the Gemini AI API. It takes an invoice image document and a prompt as input and returns the information extracted from the image as a response.

## Getting Started

Follow these steps to set up the project:

1. **Create GitHub Repository**: Create a new GitHub repository and clone it locally.

2. **Obtain API Key**: Get your API key from [here](https://makersuite.google.com/app/apikey).

3. **Set Up Virtual Environment**: Add a `requirements.txt` file with the necessary dependencies and create a virtual environment.

    ```bash
    conda create -p imgreader python==3.10 -y
    conda activate imgreader
    pip install -r requirements.txt
    ```

    Add the virtual environment directory (`imgreader/`) to `.gitignore` to exclude it from version control.

4. **Create Environment File**: Create a `.env` file and add your API key as follows:

    ```
    API_KEY="XXXXXXXXXX"
    ```

5. **Setup Application**: Set up your `app.py` file and add code to it.

## Usage

After completing the setup steps, run your application. It should be able to take an invoice image document and a prompt as input and return the extracted information from the image as a response.

## Contributors

- [Vikash Das](https://github.com/vikashishere)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

