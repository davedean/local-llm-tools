# local-llm-tools
Local LLM Tools

## LLM Hosting/Access:

[Ollama](http://ollama.com) - Run LLMs locally.

[Lite-LLM](https://litellm.vercel.app) - Provide access to hosted LLMs, and expose an Open-ai compatible API for Open-Webui.

[Openrouter](http://openrouter.ai) - API Provider for almost any hosted LLM. One account to manage, hundreds of models available.

## LLM Clients:

[Open-Webui](https://github.com/open-webui/open-webui) - Provides a webui and other features (document library/querying, prompt library .. )

[simonw/llm](https://github.com/simonw/llm) - Command Line interface to LLMs. Uses plugins to support LLMs of many kinds.

## Local Models:

Primarily, I prefer two model families at the moment - Qwen2.5 and Llama3.

LLMs capabilities follow their parameter numbers. The bigger the model, the more "world knowledge" it will have, and the less likely it will be to get confused in general.

### Choosing a model size:

Work out what model size you can fit into your available RAM/VRAM.
Try out the largest from Llama3 or Qwen2.5 that will fit.
If it's too slow, drop down a model size.
