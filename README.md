# cv_rag
a repo for a rag project

demo link: https://www.youtube.com/watch?v=L5B2q7yElWs

## How to run

Create .env file in projects root folder:

'''
OPENAI_API_KEY=sk-proj-***

AGENT_MODEL=gpt-3.5-turbo

CHATBOT_URL=http://host.docker.internal:8005/cv-rag-agent
'''

Add your pdfs to cv_rag/chromadb_etl/data folder

Build with docker:

'''console
docker-compose up --build
'''

In development:
- locally run model instead of OpenAI API