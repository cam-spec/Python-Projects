# Review Sentiment & Summary Tool

This notebook turns short product reviews into:
- **Sentiment** with a one-line rationale
- **Summary** (1–2 factual lines)
- **Rewrite** (clearer, neutral rephrasing)

Built while taking *ChatGPT Prompt Engineering for Developers (DeepLearning.AI & OpenAI)*.

## How to run
1. Create a .env **next to the notebook** with:
   \\\
   OPENAI_API_KEY=sk-...
   \\\
2. Install deps:
   \\\
   pip install openai python-dotenv pandas
   \\\
3. Open the notebook and run cells top-to-bottom.

> Note: .env is ignored by git via .gitignore.

## What I practiced
- Short, testable prompts
- Safe key handling with python-dotenv
- A tiny helper to call the OpenAI Responses API
- Compact pandas table + optional CSV export
