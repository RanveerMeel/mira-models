# Mira models

Backup download source for the on-device AI models used by **Mira**, a private assistant that runs entirely on the phone.

Mira downloads models from their official Hugging Face repositories first, and uses the releases in this repository only as a fallback.
Every file is verified against the SHA-256 checksum built into the app before it is used. A file from this mirror is accepted only if it is byte-for-byte identical to the official one.

| File | Source | License | SHA-256 |
|---|---|---|---|
| `qwen2.5-1.5b-instruct-q4_k_m.gguf` | [Qwen/Qwen2.5-1.5B-Instruct-GGUF](https://huggingface.co/Qwen/Qwen2.5-1.5B-Instruct-GGUF) | Apache-2.0 | `6a1a2eb6d15622bf3c96857206351ba97e1af16c30d7a74ee38970e434e9407e` |

Model weights are © their respective authors and redistributed under their licenses.
