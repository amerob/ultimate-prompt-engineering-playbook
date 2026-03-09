# 🚀 Ultimate Prompt Engineering Playbook

![GitHub stars](https://img.shields.io/github/stars/amerob/ultimate-prompt-engineering-playbook?style=social)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Last Commit](https://img.shields.io/github/last-commit/amerob/ultimate-prompt-engineering-playbook)
[![Open All In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/)

> A curated collection of **114 interactive Jupyter notebooks** teaching every prompt engineering technique for ChatGPT, Claude, Gemini, and more.

---

## ✨ Key Features

- **📖 Clear Explanations** — Each technique explained with theory and intuition
- **💻 Runnable Code** — Every notebook works in Google Colab with one click
- **🌍 Real-World Examples** — Practical scenarios you'll actually encounter
- **❌ Failure Cases** — Learn when techniques break and why
- **📊 Benchmarks** — Quantitative and qualitative performance comparisons
- **🎮 Interactive Playground** — Try every technique with your own prompts
- **🤖 Multi-Model** — Examples for OpenAI GPT-4, Anthropic Claude, and Google Gemini

---

## 🚀 How to Use

### Option 1: Google Colab (Recommended)
1. Click the **"Open in Colab"** badge on any notebook below
2. Enter your API keys when prompted (uses `getpass` — never stored)
3. Run cells and experiment!

### Option 2: Local Setup
```bash
git clone https://github.com/amerob/ultimate-prompt-engineering-playbook.git
cd ultimate-prompt-engineering-playbook
pip install -r requirements.txt
jupyter notebook
```

---

## 📚 Table of Contents (114 Techniques)


### Foundational Prompting
📁 [`notebooks/01-foundational/`](notebooks/01-foundational/)

| # | Technique | Notebook |
|---|-----------|----------|
| 1 | Zero-Shot Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/01-foundational/01_zero_shot_prompting.ipynb) |
| 2 | Direct Instruction | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/01-foundational/02_direct_instruction.ipynb) |
| 3 | System Prompt Engineering | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/01-foundational/03_system_prompt_engineering.ipynb) |
| 4 | Template Filling | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/01-foundational/04_template_filling.ipynb) |
| 5 | Completion Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/01-foundational/05_completion_prompting.ipynb) |
| 6 | Contextual Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/01-foundational/06_contextual_prompting.ipynb) |
| 7 | Question Refinement | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/01-foundational/07_question_refinement.ipynb) |
| 8 | Summarization Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/01-foundational/08_summarization_prompting.ipynb) |
| 9 | Keyword Extraction | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/01-foundational/09_keyword_extraction.ipynb) |
| 10 | Sentiment Analysis Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/01-foundational/10_sentiment_analysis_prompting.ipynb) |
| 11 | Text Classification | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/01-foundational/11_text_classification.ipynb) |
| 12 | Paraphrasing | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/01-foundational/12_paraphrasing.ipynb) |

### Reasoning & Logic
📁 [`notebooks/02-reasoning/`](notebooks/02-reasoning/)

| # | Technique | Notebook |
|---|-----------|----------|
| 13 | Decomposed Prompting (DecomP) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/02-reasoning/13_decomposed_prompting.ipynb) |
| 14 | Chain-of-Thought (CoT) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/02-reasoning/14_chain_of_thought.ipynb) |
| 15 | Zero-Shot Chain-of-Thought | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/02-reasoning/15_zero_shot_cot.ipynb) |
| 16 | Self-Consistency (CoT-SC) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/02-reasoning/16_self_consistency.ipynb) |
| 17 | Tree of Thoughts (ToT) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/02-reasoning/17_tree_of_thoughts.ipynb) |
| 18 | Graph of Thoughts (GoT) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/02-reasoning/18_graph_of_thoughts.ipynb) |
| 19 | Program of Thoughts (PoT) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/02-reasoning/19_program_of_thoughts.ipynb) |
| 20 | Recursive Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/02-reasoning/20_recursive_prompting.ipynb) |
| 21 | Analogical Reasoning | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/02-reasoning/21_analogical_reasoning.ipynb) |
| 22 | Maieutic Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/02-reasoning/22_maieutic_prompting.ipynb) |
| 23 | Contrastive Chain-of-Thought | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/02-reasoning/23_contrastive_cot.ipynb) |
| 24 | Stepwise Refinement | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/02-reasoning/24_stepwise_refinement.ipynb) |

### Few-Shot & Example-Based
📁 [`notebooks/03-few-shot/`](notebooks/03-few-shot/)

| # | Technique | Notebook |
|---|-----------|----------|
| 25 | Few-Shot Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/03-few-shot/25_few_shot_prompting.ipynb) |
| 26 | One-Shot Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/03-few-shot/26_one_shot_prompting.ipynb) |
| 27 | Few-Shot with Chain-of-Thought | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/03-few-shot/27_few_shot_cot.ipynb) |
| 28 | Dynamic Few-Shot Selection | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/03-few-shot/28_dynamic_few_shot.ipynb) |
| 29 | Example Ordering & Formatting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/03-few-shot/29_example_ordering.ipynb) |
| 30 | Negative Examples | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/03-few-shot/30_negative_examples.ipynb) |
| 31 | k-NN Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/03-few-shot/31_knn_prompting.ipynb) |
| 32 | Pattern-Based Few-Shot | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/03-few-shot/32_pattern_based_few_shot.ipynb) |

### Role-Playing & Persona
📁 [`notebooks/04-role-playing/`](notebooks/04-role-playing/)

| # | Technique | Notebook |
|---|-----------|----------|
| 33 | Persona Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/04-role-playing/33_persona_prompting.ipynb) |
| 34 | Expert Panel Simulation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/04-role-playing/34_expert_panel.ipynb) |
| 35 | Audience Adaptation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/04-role-playing/35_audience_adaptation.ipynb) |
| 36 | Debate Simulation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/04-role-playing/36_debate_simulation.ipynb) |
| 37 | Historical Figure Simulation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/04-role-playing/37_historical_figure_simulation.ipynb) |
| 38 | Collaborative Agents | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/04-role-playing/38_collaborative_agents.ipynb) |
| 39 | Interview Simulation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/04-role-playing/39_interview_simulation.ipynb) |
| 40 | Empathetic Response Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/04-role-playing/40_empathetic_response.ipynb) |

### Output Control & Formatting
📁 [`notebooks/05-output-control/`](notebooks/05-output-control/)

| # | Technique | Notebook |
|---|-----------|----------|
| 41 | JSON Mode / Structured Output | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/05-output-control/41_json_mode.ipynb) |
| 42 | XML / HTML Output Formatting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/05-output-control/42_xml_html_output.ipynb) |
| 43 | Markdown Formatting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/05-output-control/43_markdown_formatting.ipynb) |
| 44 | Length Control | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/05-output-control/44_length_control.ipynb) |
| 45 | Bullet Point & List Formatting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/05-output-control/45_bullet_point_formatting.ipynb) |
| 46 | Table Formatting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/05-output-control/46_table_formatting.ipynb) |
| 47 | Code Output Formatting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/05-output-control/47_code_output_formatting.ipynb) |
| 48 | Multi-Format Output | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/05-output-control/48_multi_format_output.ipynb) |
| 49 | Constrained Vocabulary | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/05-output-control/49_constrained_vocabulary.ipynb) |
| 50 | Citation Formatting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/05-output-control/50_citation_formatting.ipynb) |

### Iterative & Refinement
📁 [`notebooks/06-iterative/`](notebooks/06-iterative/)

| # | Technique | Notebook |
|---|-----------|----------|
| 51 | Iterative Refinement | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/06-iterative/51_iterative_refinement.ipynb) |
| 52 | Feedback Loop Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/06-iterative/52_feedback_loop.ipynb) |
| 53 | Progressive Disclosure | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/06-iterative/53_progressive_disclosure.ipynb) |
| 54 | Multi-Turn Conversation Design | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/06-iterative/54_multi_turn_design.ipynb) |
| 55 | Prompt Chaining | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/06-iterative/55_prompt_chaining.ipynb) |
| 56 | Draft-Critique-Revise | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/06-iterative/56_draft_critique_revise.ipynb) |
| 57 | Expansion Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/06-iterative/57_expansion_prompting.ipynb) |
| 58 | Compression-Then-Expansion | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/06-iterative/58_compression_expansion.ipynb) |

### Retrieval & Knowledge-Augmented
📁 [`notebooks/07-retrieval/`](notebooks/07-retrieval/)

| # | Technique | Notebook |
|---|-----------|----------|
| 59 | Retrieval-Augmented Generation (RAG) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/07-retrieval/59_rag.ipynb) |
| 60 | Document Grounding | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/07-retrieval/60_document_grounding.ipynb) |
| 61 | Web Search Integration | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/07-retrieval/61_web_search_integration.ipynb) |
| 62 | Knowledge Graph Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/07-retrieval/62_knowledge_graph_prompting.ipynb) |
| 63 | Multi-Document Synthesis | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/07-retrieval/63_multi_document_synthesis.ipynb) |
| 64 | Fact Verification Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/07-retrieval/64_fact_verification.ipynb) |
| 65 | Contextual Window Management | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/07-retrieval/65_context_window_management.ipynb) |

### Self-Correction & Verification
📁 [`notebooks/08-self-correction/`](notebooks/08-self-correction/)

| # | Technique | Notebook |
|---|-----------|----------|
| 66 | Self-Refine | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/08-self-correction/66_self_refine.ipynb) |
| 67 | Self-Verification | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/08-self-correction/67_self_verification.ipynb) |
| 68 | Reflection Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/08-self-correction/68_reflection_prompting.ipynb) |
| 69 | Constitutional AI Principles | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/08-self-correction/69_constitutional_ai.ipynb) |
| 70 | Confidence Calibration | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/08-self-correction/70_confidence_calibration.ipynb) |
| 71 | Error Analysis Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/08-self-correction/71_error_analysis.ipynb) |
| 72 | Consensus Checking | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/08-self-correction/72_consensus_checking.ipynb) |
| 73 | Socratic Self-Questioning | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/08-self-correction/73_socratic_self_questioning.ipynb) |

### Adversarial & Robustness
📁 [`notebooks/09-adversarial/`](notebooks/09-adversarial/)

| # | Technique | Notebook |
|---|-----------|----------|
| 74 | Red Teaming Prompts | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/09-adversarial/74_red_teaming.ipynb) |
| 75 | Adversarial Prompt Testing | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/09-adversarial/75_adversarial_testing.ipynb) |
| 76 | Jailbreak Defense | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/09-adversarial/76_jailbreak_defense.ipynb) |
| 77 | Prompt Injection Defense | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/09-adversarial/77_prompt_injection_defense.ipynb) |
| 78 | Bias Detection Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/09-adversarial/78_bias_detection.ipynb) |
| 79 | Robustness Testing | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/09-adversarial/79_robustness_testing.ipynb) |
| 80 | Safety Guardrails | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/09-adversarial/80_safety_guardrails.ipynb) |

### Optimization & Efficiency
📁 [`notebooks/10-optimization/`](notebooks/10-optimization/)

| # | Technique | Notebook |
|---|-----------|----------|
| 81 | Prompt Compression | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/10-optimization/81_prompt_compression.ipynb) |
| 82 | Token Optimization | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/10-optimization/82_token_optimization.ipynb) |
| 83 | Batch Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/10-optimization/83_batch_prompting.ipynb) |
| 84 | Caching Strategies | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/10-optimization/84_caching_strategies.ipynb) |
| 85 | Prompt Templates & Variables | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/10-optimization/85_prompt_templates.ipynb) |
| 86 | A/B Testing Prompts | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/10-optimization/86_ab_testing_prompts.ipynb) |
| 87 | Cost-Performance Tradeoff | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/10-optimization/87_cost_performance_tradeoff.ipynb) |
| 88 | Latency Optimization | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/10-optimization/88_latency_optimization.ipynb) |

### Domain-Specific Techniques
📁 [`notebooks/11-domain-specific/`](notebooks/11-domain-specific/)

| # | Technique | Notebook |
|---|-----------|----------|
| 89 | Medical Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/11-domain-specific/89_medical_prompting.ipynb) |
| 90 | Legal Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/11-domain-specific/90_legal_prompting.ipynb) |
| 91 | Code Generation Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/11-domain-specific/91_code_generation.ipynb) |
| 92 | Educational Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/11-domain-specific/92_educational_prompting.ipynb) |
| 93 | Financial Analysis Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/11-domain-specific/93_financial_analysis.ipynb) |
| 94 | Scientific Research Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/11-domain-specific/94_scientific_research.ipynb) |
| 95 | Creative Writing Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/11-domain-specific/95_creative_writing.ipynb) |
| 96 | Data Analysis Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/11-domain-specific/96_data_analysis.ipynb) |

### Meta-Prompting & Advanced
📁 [`notebooks/12-meta-prompting/`](notebooks/12-meta-prompting/)

| # | Technique | Notebook |
|---|-----------|----------|
| 97 | Meta-Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/12-meta-prompting/97_meta_prompting.ipynb) |
| 98 | Automatic Prompt Engineer (APE) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/12-meta-prompting/98_automatic_prompt_engineer.ipynb) |
| 99 | Prompt Ensembling | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/12-meta-prompting/99_prompt_ensembling.ipynb) |
| 100 | Chain-of-Density Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/12-meta-prompting/100_chain_of_density.ipynb) |
| 101 | Skeleton-of-Thought | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/12-meta-prompting/101_skeleton_of_thought.ipynb) |
| 102 | Least-to-Most Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/12-meta-prompting/102_least_to_most.ipynb) |
| 103 | Self-Ask | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/12-meta-prompting/103_self_ask.ipynb) |
| 104 | Emotional Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/12-meta-prompting/104_emotional_prompting.ipynb) |
| 105 | Rephrase and Respond (RaR) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/12-meta-prompting/105_rephrase_and_respond.ipynb) |
| 106 | Thread-of-Thought (ThoT) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/12-meta-prompting/106_thread_of_thought.ipynb) |

### Multi-Modal Prompting
📁 [`notebooks/13-multi-modal/`](notebooks/13-multi-modal/)

| # | Technique | Notebook |
|---|-----------|----------|
| 107 | Image + Text Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/13-multi-modal/107_image_text_prompting.ipynb) |
| 108 | Chart & Graph Analysis | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/13-multi-modal/108_chart_graph_analysis.ipynb) |
| 109 | Document Understanding | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/13-multi-modal/109_document_understanding.ipynb) |
| 110 | Visual Chain-of-Thought | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/13-multi-modal/110_visual_cot.ipynb) |
| 111 | Multi-Image Comparison | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/13-multi-modal/111_multi_image_comparison.ipynb) |
| 112 | Audio Transcription Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/13-multi-modal/112_audio_transcription.ipynb) |
| 113 | Video Understanding Prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/13-multi-modal/113_video_understanding.ipynb) |
| 114 | Cross-Modal Transfer | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amerob/ultimate-prompt-engineering-playbook/blob/main/notebooks/13-multi-modal/114_cross_modal_transfer.ipynb) |

---

## 🤝 Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:
- Adding new techniques
- Improving existing notebooks
- Reporting issues
- Suggesting enhancements

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## ⭐ Star History

If you find this useful, please star the repo! It helps others discover these resources.

---

Built with ❤️ for the AI community
