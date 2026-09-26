# Macedonian–English Code-Switching Evaluation

This project investigates how large language models understand text that mixes Macedonian and English, with a focus on Macedonian as a low-resource language. The dataset contains 895 aligned examples derived from the English and Macedonian versions of the Belebele reading-comprehension benchmark. Each example includes two monolingual versions and two code-switched variants: English with Macedonian insertions and Macedonian with English insertions. Six models from the Qwen, Llama, Mistral, and ALLaM families are evaluated on multiple-choice questions. Performance is compared using accuracy, changes from the monolingual baselines, and paired statistical tests. The aim is to examine whether the direction of code-switching affects comprehension.

## Results

Macedonian insertions into English reduced accuracy across all six models by 2.35–7.04 percentage points, with statistically significant decreases after correction for multiple comparisons. English insertions into Macedonian produced smaller, model-dependent changes, none of which were statistically significant. These results suggest that the effect of code-switching depends on its direction.

## Repository Structure

- **Dataset CSV:** The evaluation dataset, stored in the repository root.
- **`notebooks/`:** Two notebooks covering the primary three-model evaluation and the extended six-model evaluation and analysis.
