# Code Agent

This is a very barebones POC code agent that uses LLM chat endpoints to generate code, then allows for optional execution of the resulting code.

NOTE: check generated code before running it! There is no safety here and something like `sudo rm -rf /` would be possible.

- The code use the OpenAI python library for chat completions. It's very easy to use the same functionality for other endpoints or local models.

- Lots of hardcoded stuff here, so to use with other endpoints you would want to change the model-name used, then set the environment variables
- `OPENAI_API_KEY` and `OPENAI_BASE_URL`


