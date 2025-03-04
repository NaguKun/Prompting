# 5. Reading & Interpretation

## 5.1. NLI (Natural Language Inference)
**"Create training questions that require logical inference based on time-related statements. Each question must:**  
- Provide a short passage with explicit and implicit time relations.  
- Include a multiple-choice question requiring inference (e.g., "Based on the passage, which event happened first?").  
- Cover different types of reasoning:  
  - Temporal contradiction detection (e.g., an event occurring before it was scheduled).  
  - Sequence inference (determining the order of events).  
  - Conditional time reasoning (if X happened before Y, what follows?).  
- Feature varying levels of difficulty, from straightforward to multi-step inferences.  
- Include real-world contexts: scheduling conflicts, historical timelines, procedural steps.  

**Only provide the passage and the question, without giving the answer."**  

## 5.2. Multi-Step Reasoning
**"Create training questions that require multiple reasoning steps to resolve temporal information. Each question must:**  
- Contain a passage with a complex timeline or sequence of events.  
- Require synthesizing information from different parts of the passage.  
- Include multi-step deductions (e.g., "If A happened before B, and B was two days before C, when did A occur?").  
- Use a variety of question formats:  
  - Open-ended questions requiring explanation.  
  - Multiple-choice with closely related options.  
  - True/false statements about inferred timelines.  
- Cover various contexts: legal cases, historical analysis, scheduling conflicts, cause-effect sequences.  
- Occasionally include misleading or irrelevant details to test comprehension.  

**Only provide the passage and the question, without giving the answer."**  