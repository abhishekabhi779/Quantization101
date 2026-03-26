I run `lmstudio-community/Qwen3.5-9B-GGUF` locally in LM Studio because it works offline, keeps inference on-device, and ensures my prompts never leave my machine. [1](https://lmstudio.ai/docs/app/offline)
Quantization makes that possible by shrinking model weights, reducing memory and storage needs compared with higher-precision formats. [2](https://ngrok.com/blog/quantization)
ngrok’s quantization deep dive shows why this works so well: smaller models, faster inference, and only modest quality trade-offs when done properly. [2](https://ngrok.com/blog/quantization)
On my Ryzen laptop with an RX 6800M XT 12GB GPU, this setup delivers roughly 80 tokens/sec in everyday use.
That makes 8-bit Qwen3.5-9B GGUF my preferred balance of privacy, speed, and local model quality.
