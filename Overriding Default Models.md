# Differentiate from normal Claude

## Color

Use ``/color red`` for normal Claude code to remember it spends real money and real usage budget. For free models sessions use ``/color yellow``.
## Rename

Use ``/rename DEFAULT: My Normal Session`` to remember it's the normal Claude that spends money. For free models sessions use ``/rename OLLAMA: My free Session``.
# Ollama
## gemma4:e2b

ANTHROPIC_AUTH_TOKEN=ollama ANTHROPIC_BASE_URL=http://localhost:11434 ANTHROPIC_API_KEY="" ANTHROPIC_DEFAULT_OPUS_MODEL=gemma4:e2b ANTHROPIC_DEFAULT_SONNET_MODEL=gemma4:e2b ANTHROPIC_DEFAULT_HAIKU_MODEL=gemma4:e2b CLAUDE_CODE_SUBAGENT_MODEL=gemma4:e2b claude --model gemma4:e2b --effort high

# Open Router
## Free Router

ANTHROPIC_AUTH_TOKEN="$OPENROUTER_API_KEY" ANTHROPIC_BASE_URL="https://openrouter.ai/api" ANTHROPIC_API_KEY="" claude --model openrouter/free
