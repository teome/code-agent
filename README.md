# Code Agent

This is a very barebones POC code agent that uses LLM chat endpoints to generate code, then allows for optional execution of the resulting code.

## Using other endpoints:
- The code use the OpenAI python library for chat completions. It's very easy to use the same functionality for other endpoints or local models.

- To use with other endpoints change the model-name used and set the environment variables:
    - `OPENAI_API_KEY` and `OPENAI_BASE_URL`

## NOTE:
- Check generated code before running it! There is no safety here and something like `sudo rm -rf /` would be possible. Run in docker to be safe.


