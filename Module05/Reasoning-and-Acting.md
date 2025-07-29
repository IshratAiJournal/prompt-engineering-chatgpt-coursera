Prompt Engineering Module 5: Reasoning and Acting

🔍 Module Focus

Enhancing the reasoning abilities of AI through structured prompting techniques and understanding how LLMs combine thought and action.

🧠 Key Concepts

1. Chain-of-Thought (CoT) Prompting

A method where the prompt includes a series of intermediate reasoning steps.

Useful in arithmetic, commonsense, and symbolic reasoning tasks.

Works best with very large models (100B+ parameters).

🧪 Example (Math):

Q: Roger has 5 tennis balls. He buys 2 more cans. Each can has 3 balls. How many now?

A: Roger started with 5 balls. 2 cans of 3 is 6 balls. 5 + 6 = 11. The answer is 11.

💡 Benefits:

Encourages step-by-step logic.

Helps debug reasoning errors.

Makes AI's thought process interpretable.

2. Chain-of-Thought vs Standard Prompting

CoT dramatically outperforms standard prompting in reasoning tasks.

Shown to double performance on GSM8K dataset.

3. When CoT Works Best

Problems needing multiple steps.

Larger LLMs like PaLM-540B or GPT-3/4 perform better.

Doesn’t help small models — they often hallucinate steps.
