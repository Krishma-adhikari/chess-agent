# Chalakh Chess Agent

Chalakh is an AI chess instructor powered by Google Gemini. It helps players understand chess fundamentals, analyze positions and games, explore tactics, and improve through clear, encouraging explanations.

## Live demo

**[Try the Chalakh AI Chess Platform](https://chalakh-ai-chess-platform.ai.studio/)**

> The chess agent was built by the author. The dashboard was built completely with AI using a prompt in Google AI Studio.

## Features

- Teaches the board, pieces, rules, check, checkmate, and stalemate
- Adapts explanations for beginner and experienced players
- Explains why a move is strong instead of only suggesting what to play
- Analyzes positions and games
- Suggests candidate moves, opponent responses, tactics, and variations
- Maintains a friendly, patient, and encouraging coaching style

## Tech stack

- JavaScript (ES modules)
- Google Gemini via `@google/genai`
- Node.js

## Run locally

### Prerequisites

- Node.js 18+
- A Google AI API key with access to the configured Gemini model

### Installation

```bash
npm install
```

Configure your Google AI API key in `Chess_agent_ai.js`, then run:

```bash
node Chess_agent_ai.js
```

The example sends a test interaction and prints Chalakh's response to the console.

## Project structure

```text
Chess_agent_ai.js  # Gemini-powered chess instructor
package.json       # Project metadata and dependencies
```

## License

ISC