## Why I run Qwen3.5-9B locally

I run `lmstudio-community/Qwen3.5-9B-GGUF` locally in **LM Studio** because it works offline, keeps inference on-device, and gives me full control over my prompts and data.

Quantization makes this practical by shrinking model weights, which reduces memory and storage requirements while still preserving strong everyday model quality.

On my **Ryzen laptop with an RX 6800M XT 12GB GPU**, this setup delivers **around 80 tokens/sec**, making it fast enough for daily coding, testing, and local AI workflows.

For me, **8-bit Qwen3.5-9B GGUF** is the sweet spot between **privacy, speed, and quality**.
