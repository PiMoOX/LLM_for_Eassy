# LLM for Essay

Persian essay generation with a multi-agent reflection workflow, built with Jupyter and any OpenAI-compatible API.

## How it works

1. **Draft agent** writes an essay on a topic you provide.
2. **Reflection agent** critiques the draft (structure, clarity, argument, style).
3. **Revision agent** rewrites the essay by addressing the critique.
4. **Interactive refinement**: you can then give your own instructions to refine the essay further (press "Enter"` to finish, "undo" to go back one version).

## Setup

1.  Install the requirements:

   ```
   pip install -r requirements.txt
   ```
2. Copy `.env.example` to `.env` and put in your own API key and base URL. Never commit `.env`.
3. Open `essay_agents.ipynb` in JupyterLab and run the cells in order.

## Notes

- All prompts require Persian output; check the final text for stray non-Persian words.
- Verify any facts, numbers or citations the model produces before using them.

## License

MIT
