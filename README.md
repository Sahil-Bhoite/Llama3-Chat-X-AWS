# Llama3 chat 💬❄️

**Llama3 chat** is an intuitive and user-friendly application that allows users to interact with their Snowflake data using natural language queries. Type in your questions or requests, and Llama3 chat will generate the appropriate SQL query and return the data you need. No more complex SQL queries or digging through tables - Llama3 chat makes it easy to access your data! By bringing data one step closer, Llama3 chat empowers users to make data-driven decisions faster and more efficiently, reducing the barriers between users and the insights they seek.

## Supported LLM's

- GPT-3.5-turbo-0125
- CodeLlama-70B
- Mistral Medium


#

## 🌟 Features

- **Conversational AI**: Harnesses ChatGPT to translate natural language into precise SQL queries.
- **Conversational Memory**: Retains context for interactive, dynamic responses.
- **Snowflake Integration**: Offers seamless, real-time data insights straight from your Snowflake database.
- **Self-healing SQL**: Proactively suggests solutions for SQL errors, streamlining data access.
- **Interactive User Interface**: Transforms data querying into an engaging conversation, complete with a chat reset option.

## 🛠️ Installation

1. Clone this repository:
https://github.com/SahilBoite/Llama3-Chat-X-AWS

2. Install the required packages:
   cd llama3chat
   pip install -r requirements.txt

3. Set up your `OPENAI_API_KEY`, `ACCOUNT`, `USER_NAME`, `PASSWORD`, `ROLE`, `DATABASE`, `SCHEMA`, `WAREHOUSE`, `SUPABASE_URL` , `SUPABASE_SERVICE_KEY` and `REPLICATE_API_TOKEN` in project directory `secrets.toml`.

4. Make sure schemas and store them in docs folder that match your database.

5. Create supabase extension, table, and function from the supabase/scripts.sql.

6. Run `python ingest.py` to convert to embeddings and store as an index file.

7. Run the Streamlit app to start chatting:
   streamlit run main.py

## 🚀 Additional Enhancements

1. **Platform Integration**: Connect Llama3 chat with popular communication platforms like Slack or Discord for seamless interaction.
2. **Voice Integration**: Implement voice recognition and text-to-speech functionality to make the chatbot more interactive and user-friendly.
3. **Advanced Analytics**: Integrate with popular data visualization libraries like Plotly or Matplotlib to generate interactive visualizations based on the user's queries (AutoGPT).


## 🤝 Contributing

Feel free to contribute to this project by submitting a pull request or opening an issue. Your feedback and suggestions are greatly appreciated!

## 📄 License


