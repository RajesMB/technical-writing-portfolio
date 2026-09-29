# API authentication

## Overview

The SupportAI API uses API keys to authenticate requests.

You must include a valid API key when making authenticated API
requests.

## API keys

Create an API key from the SupportAI dashboard.

Keep your API key secure and do not expose it in publicly accessible
code or repositories.

## Add authentication to a request

Include your API key in the `Authorization` header.

```bash
curl https://api.supportai.example/v1/agents \
  -H "Authorization: Bearer YOUR_API_KEY"
