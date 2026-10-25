# RemNO.1

Information Security undergraduate at Donghua University, Shanghai.

I work on local LLM systems, evaluation tooling, small software products, and games. I keep the engineering notes, test protocols, reproduction evidence, and release artifacts that mattered while building them.

## Selected work

### [Career Arsenal](https://github.com/zyy0212time-del/career-arsenal)

A local-first, game-inspired career asset manager for scoring, ranking, and role-specific loadouts.

Built with TypeScript and React, with an interactive demo, automated tests, bilingual content, and a public release workflow.

### [Laptop Local AI Stack](https://github.com/zyy0212time-del/laptop-local-ai-stack)

An engineering case study built around running local AI on consumer laptop hardware.

Covers runtime selection, GGUF quantization, model routing, reasoning policy, multimodal setup, benchmarking, and the trade-offs that showed up in actual use.

### [Reasoning Budget Arena](https://github.com/zyy0212time-del/reasoning-budget-arena)

A living benchmark for comparing local LLMs under frozen, reproducible reasoning-budget protocols.

The evaluation workflow includes fixed test sets, blind judging, score locking, and reproducible experiment records.

## Upstream work

I also spend time reproducing local-inference failures, tracing them into upstream projects, and validating fixes.

**MiniCPM-V**  
[#1153](https://github.com/OpenBMB/MiniCPM-V/issues/1153) ·
[validation](https://github.com/OpenBMB/MiniCPM-V/issues/1153#issuecomment-6383346201)

Reported a MiniCPM-V 4.7 GGUF/chat-template failure and verified the updated official artifact across 36 recorded runs with no recurrence.

**FreeToken**  
[#131](https://github.com/FlashML-org/FreeToken/pull/131) ·
[#196](https://github.com/FlashML-org/FreeToken/pull/196) ·
[#186](https://github.com/FlashML-org/FreeToken/issues/186)

**Hermes Agent**  
[#96360](https://github.com/NousResearch/hermes-agent/issues/96360)

Most of this work has been around GGUF inference, long prompts, MoE behavior, chat templates, Windows runtime edge cases, and reproducible validation.

## Other work

UE5 games · visual novel · WeChat Mini Program · HarmonyOS
