# Hotel-Management
Whitney Hotel Management 
hotel-chatbot-agent/
├── README.md
├── requirements.txt
├── .env.example
├── .gitignore
├── docker-compose.yml
├── pyproject.toml
├── src/
│   ├── __init__.py
│   ├── config.py
│   ├── agent/
│   │   ├── __init__.py
│   │   ├── chat_agent.py
│   │   ├── tools.py
│   │   └── memory.py
│   ├── services/
│   │   ├── __init__.py
│   │   ├── hotel_service.py
│   │   ├── booking_service.py
│   │   └── payment_service.py
│   ├── models/
│   │   ├── __init__.py
│   │   ├── hotel.py
│   │   ├── reservation.py
│   │   └── database.py
│   ├── nlp/
│   │   ├── __init__.py
│   │   ├── intent_detector.py
│   │   └── entity_extractor.py
│   ├── api/
│   │   ├── __init__.py
│   │   ├── routes.py
│   │   └── schemas.py
│   └── utils/
│       ├── __init__.py
│       └── logger.py
├── tests/
│   ├── __init__.py
│   ├── conftest.py
│   ├── test_agent.py
│   ├── test_services.py
│   └── test_nlp.py
└── data/
    ├── sample_hotels.json
    └── intents.json

    
