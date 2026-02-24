![License](https://img.shields.io/badge/license-MIT-blue.svg)
![.NET](https://img.shields.io/badge/.NET-8.0-purple)
![Telegram Bot](https://img.shields.io/badge/Telegram-Bot-blue)

# Easy Ironing

Easy Ironing is a Telegram bot that analyzes clothing care labels and fabric composition to provide practical ironing instructions.

## How It Works

1. Send a care-label photo
2. Provide fabric composition (e.g., 80% cotton 20% polyester)
3. Receive safe, structured ironing guidance

## Features

- AI-powered label interpretation
- Structured JSON responses
- Conservative safety guidance
- Secure backend infrastructure

## Tech Stack

- Azure Functions (.NET 8, isolated worker)
- OpenAI Responses API
- Telegram Bot API
- Static landing page (HTML/CSS)

## Security

API keys are stored securely using environment variables.  
Sensitive tokens are never logged.  
Restricted API keys are used with minimum required permissions.

See [SECURITY.md](SECURITY.md) for vulnerability reporting.

## License

MIT License