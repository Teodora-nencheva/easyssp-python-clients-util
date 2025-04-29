# 🔧 easySSP Utils

This module provides shared utilities for the easySSP Python clients. It contains essential functionality such as HTTP
request handling, custom exceptions, logging support, and reusable helpers that streamline the integration with the
easySSP APIs.

## ✨ Features

- ✅ Centralized request handling with retry and error management
- 🚨 Custom exception classes for clear and consistent error reporting
- 🧰 Helper utilities to support the API clients
- 📋 Designed for internal use by the easySSP Python clients

## 📦 Installation

```bash
pip install easyssp-utils
```

Or clone and install from source:

```bash
git clone https://github.com/exxcellent/easyssp-python-clients-util.git
cd easyssp-python-clients-util
pip install -e .
```

## 📁 Project Structure

```bash
easyssp_utils/
├── __init__.py
├── client/
│   ├── __init__.py
│   ├── api_client.py         # Generic API client for OpenAPI client library builds
│   ├── api_response.py       # API response object
│   ├── configuration.py      # Settings of the API client
│   ├── exceptions.py         # Exceptions for the API client
│   └── rest.py               # Performing the HTTP requests
│
├── models/
│   ├── __init__.py
│   ├── client_localized_message.py       
│   ├── error_message.py        
│   ├── localized_error_message.py        
│   └── localized_message_key.py          
```

## 🛠️ Requirements

- Python 3.11+
- easyssp Pro Edition Account

Install dependencies with:

```bash
pip install -r requirements.txt
```

or install using uv:

```bash
pip install uv
uv sync
```

## 🤝 Contributing

This module is maintained as part of the easySSP ecosystem. If you find issues or want to suggest improvements, please
open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License.