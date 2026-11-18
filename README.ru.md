<div align="center">
  <img src="assets/branding/logo.svg" width="150" alt="REV" />
  <h1>REV LLM</h1>
  <p><strong>Открытые модели. Осмысленная доработка.</strong></p>
  <p><a href="README.md">English</a> · <a href="https://huggingface.co/collections/ehristoforu/rev-llm-models">Hugging Face</a> · <a href="https://github.com/ehristoforu/rev-llm">GitHub</a></p>
</div>

---

REV LLM — независимый проект по доработке языковых и мультимодальных моделей с открытыми весами. Мы публикуем веса на Hugging Face, а здесь документируем каждый релиз.

## Модели

| Модель | Базовая модель | Профиль | Материалы |
|---|---|---|---|
| Rev-Qwen3.5-2B | [Qwen/Qwen3.5-2B](https://huggingface.co/Qwen/Qwen3.5-2B) | 2B · image-text-to-text · qwen3_5 | [Веса](https://huggingface.co/ehristoforu/rev-qwen3.5-2b) · [Техническая карточка](models/rev-qwen3.5-2b/README.ru.md) · [Сравнение бенчмарков](assets/benchmarks/rev-qwen3.5-2b_tiny-benchmarks_comparison.svg) |

## Подход

- Дорабатываем открытые чекпойнты целевым дообучением.
- Объединяем совместимые файнтюны и LoRA в готовые релизы.
- Документируем происхождение моделей, лицензии и ограничения оценок.

## Структура

| Путь | Содержимое |
|---|---|
| models/ | Карточки моделей и шаблоны |
| assets/benchmarks/ | Графики бенчмарков |
| assets/branding/ | Логотип проекта |

## Благодарности

- [Hugging Face](https://huggingface.co/) — размещение и распространение моделей.
- [Unsloth](https://unsloth.ai/) — эффективное дообучение моделей.
- [OmniMergeKit](https://github.com/mann1x/omnimergekit) и [MergeKit](https://github.com/arcee-ai/mergekit) — инструменты слияния моделей.
- [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) — оценка языковых моделей.
- [llama.cpp](https://github.com/ggml-org/llama.cpp) — локальный инференс и инструменты для GGUF.
- [Alibaba Qwen](https://github.com/QwenLM) — авторы семейства Qwen, использованного как база.

## Лицензии

Проект: [GPL-3.0](LICENSE).
