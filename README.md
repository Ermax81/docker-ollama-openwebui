# docker-ollama-openwebui

Ollama and Open-webui in containers

Ollama is an open-source app that lets you run LLMs (Large Language Models) locally with a command-line interface.

Open-webui is a web interface for Ollama.

You can find the supported models [here](https://ollama.com/library).

You will need an internet connection to pull models.


## How to pull a model

Connect to ollama container and run the following command to pull a model:
```bash
docker exec -it ollama ollama pull <model_name>
```

<model_name> can be for example:
- llama3:8b
- mistral:7b
- codellama:7b

## First connexion to Open-webui

Open your browser and go to http://localhost:3000.

Create an account with "Sign up" and then log in.
For example, you can use the following credentials:
- email: admin@admin.com
- password: admin

## First query

With you browser and after logging in, choose a mode and write a query.