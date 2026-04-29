# Predictive_Scanning_Keyboard
A one-handed, temporal input system designed for fast, intuitive text entry using predictive scanning and context-aware phrase selection.
# Predictive Scanning Keyboard




## Overview

This project explores a new approach to text input that replaces traditional spatial typing with **sequential scanning and prediction**.

Instead of pressing individual keys, the user selects from a dynamically ordered stream of **predicted words and phrases**. The system prioritizes likely continuations based on context, reducing the number of selections required to construct full sentences.

---

## Core Principles

### Temporal Input (Not Spatial)
- Input is based on **timing**, not position.
- Operates with a **single input action** (button, touch, or dwell).
- Enables efficient **one-handed use**.

---

### Prediction-First Design
- Focus on **likely next inputs**, not raw characters.
- Primary interaction is **phrase-level**, not letter-level.
- Letters and symbols are fallback only.

---

### Context-Aware Continuation
- Tracks recent input (last 1–3 words).
- Predicts:
  - next words
  - common phrases
  - grammatical connectors

**Example:**
Input: I want
Suggestions: to, a, the, to build


---

### Phrase-Based Input
- Outputs **multi-word chunks** (e.g. "want to", "build a").
- Reduces total selections required.
- Matches natural language thinking.

---

### Adaptive Scanning
- No fixed scan order.
- Predictions are:
  - shown earlier
  - displayed larger
  - held longer (dwell bias)
- Less relevant options appear later.

---

### Mode-Free Interaction
- No manual switching between:
  - letters
  - words
  - functions
- Context determines what is shown.
- Prediction replaces modes.

---

### Cognitive Ergonomics
- Slower scanning, but fewer decisions.
- Visual hierarchy:
  - current item (highlighted)
  - next predicted item (emphasized)
- Designed for anticipation and reduced mental load.

---

## System Architecture

### Input
- Single or minimal input source
  - button
  - capacitive touch
  - dwell detection

### Processing
- Context tracking
- Prediction engine (rule-based or adaptive)
- Dynamic scan ordering

### Output
- Text generation (phrases, words, characters)
- Optional: HID keyboard output

---

## Key Differentiators

- Temporal input vs spatial typing
- Phrase prediction vs character entry
- Adaptive scanning vs fixed layouts
- Implicit modes vs manual switching
- Speed achieved by **reducing choices**, not increasing input rate

---

## Goal

To enable fast, low-effort sentence construction by aligning input with **natural language flow**, rather than traditional keyboard structures.

---

## Status

Prototype stage:
- Python (Tkinter) scanning interface
- Context-based prediction in development
- Hardware integration (touch sensors / microcontrollers) planned

---

## Future Work

- Predictive phrase expansion
- Adaptive learning (user-specific patterns)
- Hardware integration (capacitive touch / embedded systems)
- HID keyboard implementation
- UI refinement and visualization improvements

---

## License

TBD
