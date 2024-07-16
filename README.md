<h1 align="center">Verão com ciência 2024</h1>

# Rasa Chatbot
Use the official [Rasa Open Source](https://rasa.com/docs/rasa/) documentation to see more detailed and accurate information.
## Installation
To install on Windows, Linux, or Mac, use the information available in [Rasa installation](https://rasa.com/docs/rasa/installation/environment-set-up/).
## Useful commands
Create a new model:
```bash
rasa init
```

Train a new model based on the last changes made:
```bash
rasa train
```

Run the chatbot using the command terminal:
```bash
rasa shell
```

Run the chatbot using the interface:
```bash
rasa run -m models --enable-api --cors "*"
```

Run custom actions (must be run in a new terminal):
```bash
rasa run actions
```

Validate the modifications made to the code and check for any errors before training occurs:
```bash
rasa data validate
```

Run the chatbot in debug mode and check each action it performs:
```bash
rasa interactive 
```
Restart the conversation:
```bash
/restart
```

Leave the conversation:
```bash
/exit
```
___
