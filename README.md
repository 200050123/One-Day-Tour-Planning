# One-Day-Tour-Planning
The application will be a chat-based system to help users plan a one-day tour in any city. The key features involve:

├── backend
│   ├── main.py               # FastAPI app with endpoints
│   ├── database.py           # Neo4j connection setup
│   ├── models.py             # Pydantic models
│   ├── llm_utils.py          # Functions for LLM processing
│   └── itinerary_utils.py    # Itinerary generation and optimization
├── frontend
│   └── app.py                # Streamlit interface


# Run the Application

uvicorn backend.main:app --reload
streamlit run frontend/app.py
