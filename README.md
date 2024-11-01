# BlogWiseAgent

**BlogWiseAgent** is an intelligent chatbot that stores blog embeddings from provided URLs and efficiently routes queries. It uses the Astra Vector DB to enhance knowledge retrieval and provides accurate responses by leveraging two agents: a database agent for blog-related inquiries and a wiki agent for general knowledge.

## Requirements

To run this project, you need the following keys:

- `GROQ_API_KEY`
- `ASTRA_DB_APPLICATION_TOKEN`
- `ASTRA_DB_ID`

Store these keys in a `.env` file in the root directory of the project.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/MaazLab/BlogWiseAgent.git
   cd BlogWiseAgent

2. **Install Dependencies**

    Use the following command to install required libraries:
    
    ```bash
    pip install -r requirements.txt

3. **Set Up API Key**
    
    - Create a ```.env``` file in the root directory of the project.
    - Add your API key to the ```.env``` file as follows:
    ```bash
    GROQ_API_KEY=your_groq_api_key_here
    ASTRA_DB_APPLICATION_TOKEN=your_astra_db_application_token
    ASTRA_DB_ID=your_astra_db_id

## Models Used
- Chatbot Model: `Gemma2-9b-It`
- Embedding Model: `all-MiniLM-L6-v2`

## Future Plans
1. Transform this notebook into a proper application.
2. Create a user-friendly interface using Streamlit or Gradio to demonstrate the workings of the agents and the final response.
3. Provide flexibility to allow users to input their own blog URLs.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute this software for both commercial and non-commercial purposes, as long as you include the original license. See the [LICENSE](LICENSE) file for full details.

