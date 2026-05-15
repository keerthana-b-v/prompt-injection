# Prompt Injection Defense Lab

Hands-on exploration of prompt injection attacks and defenses using Lakera Gandalf + Anthropic Console.

## 🚀 Overview
This repository documents my progress through the levels of [Lakera Gandalf](https://gandalf.lakera.ai/), where I learned to bypass AI safety filters and, more importantly, how to build prompts that resist these attacks.

## 🧠 What I Did
- **Completed 7 levels** of Lakera Gandalf.
- **Documented each attack technique** used to extract secrets.
- **Built hardened system prompts** that block each specific attack vector.

## 🛡️ Attacks Covered
1. **Role Override (DAN-style)**: Forcing the AI into a lawless persona.
2. **Instruction Ignore**: "Ignore previous instructions and do X."
3. **Indirect Injection**: Hiding instructions within data or structured formats.

## 💡 Key Learning
A strong system prompt must explicitly address edge cases—vague instructions always get exploited. Using "Delimiters" and "Absolute Constraints" is the only way to ensure safety.

## 📊 Evaluation (Evals)
Testing prompts systematically is crucial. For this lab, I followed a basic 3-step eval process:
1. **Systematic Testing**: Tested prompts against 5-10 varied user inputs.
2. **Scoring**: Evaluated outputs for accuracy, consistency, and format compliance.
3. **Refinement**: Hardened the system prompt based on failed test cases.

## 🛠️ Tools Used
- **Lakera Gandalf**: [gandalf.lakera.ai](https://gandalf.lakera.ai/)
- **Anthropic Console**: [console.anthropic.com](https://console.anthropic.com/)
- **Prompting Guide**: [promptingguide.ai/prompts/evaluation](https://www.promptingguide.ai/prompts/evaluation)

---
*Created as part of the Prompt Engineering Learning Journey.*
