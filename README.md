# Physics AI Reasoning Dataset

A small but high-quality dataset of graduate/PhD-level physics questions with full step-by-step solutions, generated using OpenRouter AI (`x-ai/grok-4.1-fast:free`).

## Dataset

- **File:** `physics_reasoning_dataset.csv`  
- **Columns:** `question`, `answer`  
- **Topics:** Quantum Mechanics, Relativity, Statistical Mechanics, Field Theory, Condensed Matter

## Generation

- Model: Free, fast, high-rate-limit AI  
- Runtime: ~6 minutes  
- Each entry contains one rigorous question and its full solution.

## FAQ

**Q: Why is the dataset so short (~5 minutes runtime)?**  
A: To avoid token overload and API rate limits. Long questions consume more tokens and can slow or fail the run.

**Q: Why do some answers cut off?**  
A: Maximum token limits or network timeouts may truncate the AI’s output.

**Q: Why only two columns?**  
A: Simplicity — each row is one question-answer pair for easy parsing.
