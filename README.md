# QuickBooks RAG Analyst (MVP)

A simple Flask app to connect to QuickBooks Online via OAuth2, pull basic financial reports, and display them. Serves as a foundation for building a RAG-based financial analyst for mid-size businesses.

## Features
- OAuth2 login with QuickBooks
- Fetches Profit & Loss reports from the QuickBooks API
- Displays data for future use in AI models (e.g. RAG)

## Setup
1. Clone the repo into Replit or your local machine.
2. Create a QuickBooks app at [developer.intuit.com](https://developer.intuit.com).
3. Set the following environment variables (see `.env.example`)
4. Run the app.

## Future Plans
- Add vector storage + embeddings for financial docs
- Integrate OpenAI or other LLMs for query analysis
- Add endpoints to handle chat + financial summarization