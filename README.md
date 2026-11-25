# Jinjia (Mars) Zheng

I'm a Software Engineering undergraduate at **East China Normal University** (expected graduation: June 2027) and a former Computer Science exchange student at **UC Berkeley** (2025–2026). I am applying for graduate study, with interests in reliable AI agents and intelligent systems that connect software, devices, and people.

My projects span agent workflows, embedded voice interaction, and on-device photo analysis. They have led me to questions about how intelligent systems use evidence, recover from failures, and work within practical resource constraints.

## Research interests

- **AI agents and evaluation:** Learning from execution experience, tool use, memory, and controlled evaluation of whether improvements transfer to new tasks.
- **Embedded and edge–cloud intelligence:** Coordinating local sensing and interaction with cloud inference, with attention to latency, resource use, and recovery.
- **Human–AI interaction:** Making model suggestions understandable and giving users effective ways to review, correct, and control system actions.

## Current research direction

I am exploring how LLM-based agents can improve through reusable experience and changes to their execution framework. My current work focuses on designing controlled comparisons: separating memory updates from framework changes, tracking versions and execution traces, and evaluating on tasks held apart from development.

This is ongoing work. I am particularly interested in understanding which improvements generalize across tasks and domains, and what evidence is needed to attribute those improvements to a specific change.

## Selected projects

### [LAND-DATA](https://github.com/Mars-Kinga/LAND-DATA) · Agent workflows and evidence tracking

A Python/SQLite system for collecting, structuring, and reviewing place information. It combines deterministic processing with optional LLM extraction, field-level source tracking, checkpoints, and human review.

The location-verification prototype separates the agent's proposed actions from tool permissions, call budgets, and an independent completion check. Its documented replay experiments examine how conflicting or insufficient evidence is routed to review; broader agent evaluation is ongoing.

**Public source:** [Architecture](https://github.com/Mars-Kinga/LAND-DATA/blob/main/docs/architecture.md) · [Implementation and evaluation status](https://github.com/Mars-Kinga/LAND-DATA/blob/main/docs/implementation-status.md)

### [Kitchen Assistant](https://github.com/Mars-Kinga/kitchen_assistant) · Multimodal interaction and workflow control

I developed a Python guided-cooking runtime that combines local recipe lookup, validated LLM generation, image-based ingredient questions, and tutorial import. A deterministic state machine manages confirmation, cooking steps, timers, and pause/resume; users review generated or imported content before using it.

The repository includes a web console, setup scripts, and automated tests. Robot actions currently use simulated adapters.

**Public source:** [Architecture](https://github.com/Mars-Kinga/kitchen_assistant/blob/main/docs/ARCHITECTURE.md) · [Setup and tests](https://github.com/Mars-Kinga/kitchen_assistant#quick-start)

### Moby · Embedded voice interaction

An ESP32-S3 companion robot project combining local wake-word detection, FreeRTOS task coordination, display expressions, and a Python agent runtime for cloud speech recognition, tool execution, and speech synthesis.

My work on the project includes voice-pipeline integration, device feedback, and persistent memory. It motivates my interest in the interaction between embedded constraints and agent behavior. The source repository is private; end-to-end hardware validation is ongoing.

### [Picora · 轻选](https://github.com/Mars-Kinga/picora) · On-device analysis and user control

A native iPhone and iPad photo-management app I developed with Swift and SwiftUI. Vision features and OCR support local photo suggestions, while PhotoKit and SwiftData support saved review progress and explicit confirmation of library changes.

The project explores how automated recommendations can fit into a recoverable, user-controlled workflow, with incremental caching and background analysis that adapts to device conditions.

**Public overview:** [Features and screenshots](https://github.com/Mars-Kinga/picora#english) · App source is private.

## Additional engineering experience

My other work includes C#/.NET industrial data acquisition with TCP communication, binary parsing, and reconnection handling, as well as the team-built [Online Museum](https://github.com/Mars-Kinga/OnlineMuseum), a Vue-based digital museum.

**Tools I use:** Python, C/C++, Swift/SwiftUI, C#/.NET, SQL/SQLite, ESP32-S3/FreeRTOS, and automated testing.
