# Interlock Systems — Technical Assessment

## About Interlock

Interlock builds AI systems that automate the design-to-manufacturing handoff for contract manufacturers in regulated industries (aerospace, defense, medical devices). Our pipeline ingests manufacturing documents from customers and extracts, classifies, and cross-references critical data to catch errors before they reach the shop floor.

## The Task

The `/data/` folder contains 20 manufacturing documents from a customer.

Build a system that classifies them by type and evaluates how well it works.

How you define the types, how you measure quality, and how you build the system are up to you. We expect you'll have questions — ask them.

## What we're looking for

We care about your **approach and reasoning** more than a perfect result. Talk us through your decisions as you go. Use whatever language, framework, and tools you prefer.

## Setup

```bash
# Clone this repo
git clone <repo-url>
cd exercise-a

# Set up your API key (provided at the start of the session)
cp .env.example .env
# Edit .env and add the API key we gave you
```

## API Access

We've provided an OpenRouter API key that gives you access to multiple LLM models (Claude, GPT, Gemini, Llama, etc.) through a single OpenAI-compatible endpoint.

```
Base URL: https://openrouter.ai/api/v1
```

You can use any model available on OpenRouter. Some options:
- `anthropic/claude-sonnet-4-20250514` — strong reasoning
- `anthropic/claude-haiku-3-20250414` — fast and cheap
- `google/gemini-2.0-flash-001` — fast
- `meta-llama/llama-3.3-70b-instruct` — open source

Use whatever model(s) you think are appropriate. Model choice is part of the exercise.
