# Role-playing with models

> [!WARNING]
> NSFW content included in this repository, use it at your own risk.

> [!NOTICE]
> **NOT** [SillyTavern](https://sillytavernai.com) compatible character card.

System prompts and other stuff for role-playing witl models.

## Usage

1. Find out which model you want to use.

   We use `./huggingface.co/mradermacher/Peach-2.0-9B-8k-Roleplay-i1-GGUF` as an example below.

2. Download model if needed.

   Go go `https://huggingface.co/mradermacher/Peach-2.0-9B-8k-Roleplay-i1-GGUF` and download model file.

   You can also use `./huggingface.co/mradermacher/Peach-2.0-9B-8k-Roleplay-i1-GGUF/Peach-2.0-9B-8k-Roleplay.yaml` if you are using [LocalAI](https://localai.io)

   As for other models, their url is similar to this, you can build its url by following its path in the repository.

3. Ensure language and character.

   For example, `zh-cn` as language and `Vanilla-Maid` as character.

4. Get system prompt.

   It should be placed at `./huggingface.co/mradermacher/Peach-2.0-9B-8k-Roleplay-i1-GGUF/zh-cn/Vanilla-Maid.md`.

   Use **raw content** instead rendered document.

5. Set system prompt.

   Use tools like llama.cpp, ollama, etc.
   Please ensure the model is supported by the tool. Most of the time this is not a huge problem.
   Then you must set system prompt to the file mentioned before.

6. Enjoy.
