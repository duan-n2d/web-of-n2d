# My Learning Journey Repository Structure

```
my-learning-journey/
├── README.md                 # Project overview and setup instructions
├── .gitignore                # Files to ignore in git
├── docker-compose.yml        # Docker setup for development
├── backend/                  # FastAPI backend
│   ├── app/
│   │   ├── __init__.py
│   │   ├── main.py           # FastAPI app initialization
│   │   ├── config.py         # Configuration settings
│   │   ├── db/               # Database models and connections
│   │   │   ├── __init__.py
│   │   │   ├── database.py   # Database connection
│   │   │   └── models.py     # SQLAlchemy models
│   │   ├── api/              # API routes
│   │   │   ├── __init__.py
│   │   │   ├── endpoints/    # API endpoints by resource
│   │   │   │   ├── __init__.py
│   │   │   │   ├── coding.py
│   │   │   │   ├── data_analysis.py
│   │   │   │   ├── data_engineering.py
│   │   │   │   └── english.py
│   │   │   └── router.py     # API router setup
│   │   └── schemas/          # Pydantic schemas
│   │       ├── __init__.py
│   │       └── models.py     # Data validation schemas
│   ├── tests/                # Backend tests
│   │   ├── __init__.py
│   │   └── test_api.py
│   ├── requirements.txt      # Python dependencies
│   └── Dockerfile            # Backend Dockerfile
└── frontend/                 # Svelte frontend
    ├── public/               # Static files
    │   ├── favicon.ico
    │   └── global.css
    ├── src/                  # Source code
    │   ├── App.svelte        # Main app component
    │   ├── main.js           # Entry point
    │   ├── components/       # Reusable UI components
    │   │   ├── Header.svelte
    │   │   ├── Footer.svelte
    │   │   ├── Sidebar.svelte
    │   │   └── ...
    │   ├── pages/            # Page components
    │   │   ├── Home.svelte
    │   │   ├── Coding.svelte
    │   │   ├── DataAnalysis.svelte
    │   │   ├── DataEngineering.svelte
    │   │   └── English.svelte
    │   ├── stores/           # Svelte stores for state management
    │   │   └── learning.js
    │   ├── lib/              # Utility functions
    │   │   └── api.js        # API client for FastAPI backend
    │   └── styles/           # Component styles
    │       └── theme.css
    ├── package.json          # Node.js dependencies
    ├── rollup.config.js      # Svelte build configuration
    └── Dockerfile            # Frontend Dockerfile
```