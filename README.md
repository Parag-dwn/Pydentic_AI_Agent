# Pydantic AI Chatbot

This project is a **Pydantic AI Chatbot** that leverages **Craw4AI**, **Pydantic AI**, **Supabase**, and **Streamlit** to create an interactive chatbot with Retrieval-Augmented Generation (RAG) capabilities. The chatbot scrapes data from URLs and utilizes this data to answer user queries effectively. The project is designed for ease of use, data-driven responses, and a seamless UI.

---

## Features

- **Web Scraping**: Uses Craw4AI to scrape structured data from URLs.
- **Data Storage**: Stores scraped data in **Supabase** for efficient RAG searches.
- **RAG Search**: Retrieves and augments chatbot responses based on the scraped data.
- **AI Agent**: Built with Pydantic AI to ensure accurate and type-safe AI interactions.
- **User Interface**: Designed using **Streamlit** for a simple, interactive user experience.

---

## Tech Stack

- **Craw4AI**: Used for web scraping and extracting elevated details from target URLs.
- **Pydantic AI**: Ensures structured and validated data for AI agent creation.
- **Supabase**: Serves as the database for storing scraped data and facilitating RAG.
- **Streamlit**: Provides a user-friendly web interface for the chatbot.

---

## Project Structure

```
.
├── app.py                # Main Streamlit application
├── scraper.py            # Web scraping logic using Craw4AI
├── pydantic_ai_agent.py  # Pydantic AI agent logic
├── supabase_config.py    # Configuration for Supabase database
├── README.md             # Project documentation
└── requirements.txt      # Dependencies
```

---

## Installation

### Prerequisites
- Python 3.8+
- Supabase account

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/Parag-dwn/Pydentic_AI_Agent.git
   cd pydantic-ai-chatbot
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Configure **Supabase**:
   - Create a `.env` file with the following environment variables:
     ```env
     SUPABASE_URL=your-supabase-url
     SUPABASE_KEY=your-supabase-key
     ```

4. Run the application:
   ```bash
   streamlit run app.py
   ```

---

## Usage

1. Open the Streamlit UI in your browser.
2. Enter a URL for scraping.
3. The chatbot will scrape data, store it in Supabase, and provide intelligent responses based on user queries.

---

## Environment Variables
Ensure the following environment variables are set:

- `SUPABASE_URL`: Your Supabase project URL.
- `SUPABASE_KEY`: The public API key for your Supabase project.

---

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

1. Fork the project.
2. Create a new branch (`feature/your-feature-name`).
3. Commit your changes.
4. Push the branch and submit a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments

- **Craw4AI** for web scraping functionality.
- **Pydantic AI** for data validation and type-safe AI interactions.
- **Supabase** for RAG data storage.
- **Streamlit** for creating an intuitive UI.

---

## Contact

For questions or feedback, feel free to [open an issue](https://github.com/your-username/pydantic-ai-chatbot/issues) or contact the project maintainers.

