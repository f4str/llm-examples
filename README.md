# LLM Examples

Notebooks for running small open-weight instruct models locally. Each model family has its
own directory, and each guide comes in two versions: `-hf` uses Hugging Face `transformers`
on PyTorch, `-mlx` uses Apple MLX with the quantized `mlx-community` conversion of the same
model. Both cover the same material in the same order.

## Models

Each family has its own directory, listed with its transformers and MLX checkpoints.

* [Qwen 3](qwen-3/) — `Qwen/Qwen3-1.7B`
* [Gemma 4](gemma-4/) — `google/gemma-4-E2B-it`
* [Granite 4.1](granite-4.1/) — `ibm-granite/granite-4.1-3b`
* [LFM 2](lfm-2/) — `LiquidAI/LFM2-700M`
* [LFM 2.5](lfm-2.5/) — `LiquidAI/LFM2.5-350M`

## Guides

* **Basic Usage:** chat template, single turn, system prompt, multi-turn, streaming, and thinking where the model supports it
* **Tool Calling:** tool schemas, parsing tool calls, returning results; single, multiple, and sequential calls
* **Documents:** answering from supplied documents, including unanswerable questions
