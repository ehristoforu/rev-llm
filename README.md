<div align="center">
  <img src="assets/branding/logo.svg" width="150" alt="REV" />
  <h1>REV LLM</h1>
  <p><strong>Open models. Reworked with intent.</strong></p>
  <p><a href="README.ru.md">Русский</a> · <a href="https://huggingface.co/collections/ehristoforu/rev-llm-models">Hugging Face</a> · <a href="https://github.com/ehristoforu/rev-llm">GitHub</a></p>
</div>

---

REV LLM is an independent project refining open-weight language and multimodal models through fine-tuning, LoRA, and model merging. We publish model weights on Hugging Face and document each release here.

## Models

| Model | Base model | Profile | Resources |
|---|---|---|---|
| Rev-Qwen3.5-2B | [Qwen/Qwen3.5-2B](https://huggingface.co/Qwen/Qwen3.5-2B) | 2B · image-text-to-text · qwen3_5 | [Weights](https://huggingface.co/ehristoforu/rev-qwen3.5-2b) · [Technical card](models/rev-qwen3.5-2b/README.md) · [Benchmark comparison](assets/benchmarks/rev-qwen3.5-2b_tiny-benchmarks_comparison.svg) |

## Approach

- Refine capable open-weight checkpoints with targeted fine-tuning.
- Merge compatible fine-tunes and LoRA adapters into practical releases.
- Document model lineage, licenses, and evaluation limits.

## Repository

| Path | Contents |
|---|---|
| models/ | Model cards and reusable card templates |
| assets/benchmarks/ | Benchmark charts |
| assets/branding/ | Project logo |

## Acknowledgements

- [Hugging Face](https://huggingface.co/) — model hosting and distribution.
- [Unsloth](https://unsloth.ai/) — efficient model fine-tuning.
- [OmniMergeKit](https://github.com/mann1x/omnimergekit) and [MergeKit](https://github.com/arcee-ai/mergekit) — model merging tools.
- [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) — language-model evaluation.
- [llama.cpp](https://github.com/ggml-org/llama.cpp) — local model inference and GGUF tooling.
- [Alibaba Qwen](https://github.com/QwenLM) — the Qwen model family used as the base.

## License

Project: [GPL-3.0](LICENSE).
