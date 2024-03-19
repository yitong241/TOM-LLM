Running TinyLlama server with Python:

```bash
python main.py
```

Access the server with:

```bash
curl -X POST 127.0.0.1:5000/generate-text \
-H "Content-Type: application/json" \
-d "{\"messages\": [{\"role\": \"system\", \"content\": \"You are a friendly chatbot.\"}, {\"role\": \"user\", \"content\": \"<Input Question>\"}]}"
```

or with the Python script:

```bash
python access.py
```
and key in the prompt that you have.


