# e2e_chat
```bash
e2e-encrypted-chat/
├── backend/
│   ├── app/
│   │   ├── __init__.py
│   │   ├── main.py              # FastAPI app initialization
│   │   ├── config.py            # Configuration settings
│   │   ├── dependencies.py      # Dependency injection
│   │   ├── models/              # SQLAlchemy database models
│   │   ├── schemas/             # Pydantic schemas for API
│   │   ├── api/                 # API routes
│   │   │   ├── __init__.py
│   │   │   ├── auth.py          # Authentication endpoints
│   │   │   ├── users.py         # User management
│   │   │   └── chat.py          # Chat-related endpoints
│   │   ├── core/                # Core functionality
│   │   │   ├── __init__.py
│   │   │   ├── security.py      # JWT, password hashing
│   │   │   └── encryption.py    # E2E encryption utilities
│   │   └── websockets/          # WebSocket handlers
│   ├── alembic/                 # Database migrations
│   ├── tests/                   # Backend tests
│   ├── requirements.txt         # Python dependencies
│   └── Dockerfile               # Backend container
├── frontend/
│   ├── public/                  # Static files
│   ├── src/
│   │   ├── components/          # React components
│   │   ├── contexts/            # React contexts
│   │   ├── hooks/               # Custom React hooks
│   │   ├── pages/               # App pages/routes
│   │   ├── services/            # API services
│   │   ├── utils/               # Utility functions
│   │   │   └── encryption.ts    # Client-side encryption
│   │   ├── App.tsx              # Main app component
│   │   └── index.tsx            # App entry point
│   ├── package.json             # NPM dependencies
│   ├── tsconfig.json            # TypeScript config
│   └── Dockerfile               # Frontend container
├── docker-compose.yml           # Multi-container setup
├── .gitignore                   # Git ignore file
└── README.md                    # Project documentation
```
