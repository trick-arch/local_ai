Mainly storing my docker-compose file to set up ollama and openwebui with watchtower updater

Change openweb ui port if are already using localhost:8080. Ollama port 11434 is likely unused.

Need to change openwebui image(latest vs cuda) and ollama device lines if you have an AMD card. Otherwise works in "1 click" with nvidia.
