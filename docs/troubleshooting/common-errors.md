# Common errors

## Authentication failed

### Cause

The API request does not contain a valid API key.

### Solution

Verify that the `Authorization` header contains a valid SupportAI
API key.

See [API authentication](../api/authentication.md).

## Agent does not respond as expected

### Possible causes

- The agent instructions may be incomplete.
- The required knowledge source may not be configured.
- The knowledge source may not contain relevant information.

### Solution

Review the agent configuration and verify that the required
knowledge sources are available.
