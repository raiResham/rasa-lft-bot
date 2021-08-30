# rasa-lft-bot
Rasa chatbot to handle internship queries for leapfrog technologies.

### Project Structure
```bash
.
├── README.md
├── actions
│   ├── __init__.py
│   └── actions.py
├── config.yml
├── credentials.yml
├── data
│   ├── nlu.yml
│   ├── rules.yml
│   └── stories.yml
├── domain.yml
├── endpoints.yml
├── events.db
├── events.db-shm
├── events.db-wal
├── models
├── rasa.db
├── requirements.txt
└── tests
    └── test_stories.yml

```

### Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the dependencies.
```bash
pip install requirements.txt
```

### Visuals

<img src = "screenshot/chatbot_screen_shot.png" width = "500">
