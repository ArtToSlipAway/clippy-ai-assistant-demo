# Security

This repository is a sanitized portfolio version of a private production project.

It intentionally excludes:

- production credentials and API keys;
- OAuth and service-account credentials;
- personal and customer data;
- runtime databases;
- production server configuration;
- backups and logs;
- private Git history.

Secrets must be supplied through environment variables and must never be committed.
