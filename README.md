phishing-detection-app/
│
├── frontend/                # React frontend (Azure Static Web Apps)
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/                 # FastAPI backend (Azure App Service)
│   ├── app/
│   │   ├── main.py          # API routes
│   │   ├── models/          # ML integration
│   │   └── services/        # DB, Redis, Azure ML calls
│   └── requirements.txt
│
├── ai-model/                # ML pipeline
│   ├── phishing_model.ipynb # Training notebook
│   ├── inference.py         # Model inference script
│   └── environment.yml
│
├── infra/                   # Deployment configs
│   ├── azure-pipelines.yml  # Azure DevOps CI/CD
│   └── dockerfile
│
├── README.md                # Project overview
└── LICENSE
