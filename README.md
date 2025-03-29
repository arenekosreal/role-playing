# Role-playing with models

> [!WARNING]
> NSFW content included in this repository, use it at your own risk.

## local-ai

Some models not included in [LocalAI](https://localai.io)'s official gallery.

### Usage

Simply load model with `/models/apply` endpoint or run `local-ai run <model-manifest>.yaml` directly.

## system-prompts

**NOT** [SillyTavern](https://sillytavernai.com) compatible character card.

### Usage

File path match this pattern: `./system-prompts/<url-to-model>/<language-code>/<character>`

For example:

1. Find which model you want to use. Let us say you want `./system-prompts/huggingface.co/mradermacher/Peach-2.0-9B-8k-Roleplay-i1-GGUF`.
2. Find which language you want to use. We use `zh-cn` as an example here.
3. Download model if needed: `https://huggingface.co/mradermacher/Peach-2.0-9B-8k-Roleplay-i1-GGUF`
4. Find which character you want to play. For example, `Vanilla-Maid`.
5. Launch model with tools you like, such as local-ai, ollama, or even llama.cpp.
6. Set system prompt to content of file `./system-prompts/huggingface.co/mradermacher/Peach-2.0-9B-8k-Roleplay-i1-GGUF/zh-cn/Vanilla-Maid.md`.
7. Enjoy.
