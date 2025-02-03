# Lang-server-with-Groq-API

When you run the server file, swagger will open in browser.

This is an example of swagger API in postman:
API: http://127.0.0.1:8000/chain/batch

Body:{
  "inputs": [
    {
      "language": "French",
      "text": "my name is soodeh"
    }
  ],
  "config": {},
  "kwargs": {}
}

Output:{
    "output": [
        "My name is Soodeh. \n\nHere's the translation:\n\n**Je m'appelle Soodeh.**\n\n\nLet me know if you have any other phrases you'd like me to translate!\n"
    ],
    "metadata": {
        "responses": [
            {
                "run_id": "8f884c28-6111-4824-ae68-bfefbfc476ed",
                "feedback_tokens": []
            }
        ],
        "run_ids": [
            "8f884c28-6111-4824-ae68-bfefbfc476ed"
        ]
    }
}
