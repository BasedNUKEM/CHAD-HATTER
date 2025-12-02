# Copilot Instructions for CHAD-HATTER

This repository contains a Python Telegram bot for the CHAD-HATTER cryptocurrency community. The bot integrates with DexScreener, Basescan, and Twitter/X APIs to provide real-time token information and community engagement features.

## Project Overview

- **Language**: Python 3
- **Main File**: `Chadhatterbot` (main Python file, no extension)
- **Dependencies**: `tweepy`, `requests`, `python-telegram-bot`

## Coding Standards

- Follow PEP 8 style guidelines for Python code
- Use type hints where appropriate
- Use async/await patterns for asynchronous operations
- Keep functions focused and single-purpose
- Use meaningful variable and function names

## Security Guidelines

- Never commit API tokens, secrets, or credentials to the repository
- Keep placeholder values (e.g., `YOUR_TELEGRAM_TOKEN_HERE`) for sensitive configuration
- Environment variables should be used for production deployments
- Be cautious with user input handling to prevent injection attacks

## Best Practices

- Handle exceptions gracefully with appropriate error logging
- Use the existing code patterns when adding new features
- Document new functions with docstrings
- Test API integrations locally before committing

## File Structure

- Keep the main bot logic in the `Chadhatterbot` file
- Store persistent data (like `last_tweet_id.json`) separately from code
- Configuration should be at the top of files for easy modification
