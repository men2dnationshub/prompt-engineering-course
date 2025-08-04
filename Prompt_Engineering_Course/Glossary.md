
# Glossary of Prompt Engineering Terms

This glossary provides definitions for key terms and concepts used throughout this course. Understanding these terms is essential for mastering prompt engineering.

---

### A

*   **Adversarial Prompting:** The practice of creating prompts designed to test the limits of an LLM, identify vulnerabilities, or cause it to behave in unintended ways. This is often used in red teaming to improve model safety.

*   **AI Alignment:** The field of research focused on ensuring that AI systems act in ways that are consistent with human values and intentions. In prompt engineering, this involves crafting prompts that guide the model toward desired ethical and behavioral outcomes.

*   **API (Application Programming Interface):** A set of rules and protocols that allows different software applications to communicate with each other. In the context of LLMs, APIs are used to send prompts to the model and receive responses.

*   **Architecture (Model Architecture):** The underlying structure and design of a neural network or language model. Different architectures (e.g., Transformer, MoE) have different strengths and weaknesses that can influence prompt engineering strategies.

*   **Aspect Ratio:** The proportional relationship between the width and height of an image. In text-to-image generation, specifying the aspect ratio is a key part of the prompt.

*   **A/B Testing:** A method of comparing two versions of a prompt (or other variable) to determine which one performs better. This is a common technique for data-driven prompt optimization.

### B

*   **Bias (AI Bias):** Systematic errors in AI outputs that result in unfair or discriminatory treatment of certain groups or individuals. Bias can be introduced through training data, model architecture, or prompt design.

*   **Benchmark:** A standard or point of reference against which things may be compared or assessed. In prompt engineering, benchmarks are used to evaluate the performance of different prompts or models on specific tasks.

### C

*   **Chain-of-Thought (CoT) Prompting:** A prompting technique that encourages the model to explain its reasoning process step-by-step before giving a final answer. This often improves performance on complex reasoning tasks.

*   **Context Window:** The maximum amount of text (measured in tokens) that a language model can consider at one time when generating a response. The size of the context window is a key architectural feature of an LLM.

*   **Constitutional AI:** A method developed by Anthropic for training AI systems to be helpful, harmless, and honest by providing them with a set of guiding principles (a "constitution") rather than relying solely on human feedback.

*   **Custom Instructions (System Prompts):** Persistent instructions that guide the behavior of an LLM across multiple interactions. These are used to set a consistent tone, personality, or set of rules for the model.

### D

*   **Disinformation:** False information that is deliberately created and spread with the intent to deceive or cause harm.

*   **Domain-Specific:** Tailored to a particular field of knowledge or area of expertise. Domain-specific prompts are designed for tasks in fields like medicine, law, or finance.

### E

*   **Embodied AI:** AI systems that can interact with the physical world through sensors and actuators, such as robots. Prompting for embodied AI requires consideration of physical and spatial context.

*   **Evaluation Metrics:** The standards and measures used to assess the quality, accuracy, and effectiveness of LLM outputs. These can be quantitative (e.g., response time) or qualitative (e.g., coherence).

### F

*   **Few-Shot Prompting:** A prompting technique where the model is given a few examples of the desired task and output format within the prompt itself. This helps the model understand the task without requiring fine-tuning.

*   **Fine-Tuning:** The process of further training a pre-trained language model on a smaller, task-specific dataset to adapt its behavior for a particular application.

### G

*   **Generative AI:** A class of AI systems that can create new content, such as text, images, audio, and video.

### H

*   **Hallucination (AI Hallucination):** A phenomenon where an LLM generates text that is plausible-sounding but factually incorrect or nonsensical. This is a common challenge in prompt engineering.

*   **Human-in-the-Loop (HITL):** A system design where humans are involved in the AI workflow, often to review, validate, or correct AI-generated outputs. This is a key strategy for ensuring quality and safety.

### I

*   **In-Context Learning:** The ability of an LLM to learn a new task or pattern from the information provided within the prompt itself, without requiring changes to the model's underlying parameters.

*   **Instruction Following:** The ability of an LLM to understand and adhere to specific instructions provided in a prompt. This is a key capability that enables sophisticated prompt engineering.

### L

*   **Large Language Model (LLM):** A type of artificial intelligence model that has been trained on vast amounts of text data to understand and generate human-like language.

### M

*   **Meta-Prompting:** The practice of using an LLM to generate or refine prompts for other tasks. This leverages the model's own understanding of how to interact with itself effectively.

*   **Misinformation:** False or inaccurate information that is spread unintentionally, without malicious intent.

*   **Mixture of Experts (MoE):** A type of neural network architecture where multiple specialized sub-models (experts) are used, and a gating mechanism determines which expert to use for a given input. This allows for larger and more efficient models.

*   **Multimodal Model:** An AI model that can process and generate information across multiple modalities, such as text, images, and audio.

### O

*   **One-Shot Prompting:** A type of few-shot prompting where only one example is provided in the prompt.

### P

*   **Parameter (Model Parameter):** The internal variables of a language model that are learned during training. The number of parameters is often used as a measure of a model's size and complexity.

*   **Persona Prompting:** A technique where the prompt instructs the model to adopt a specific role, personality, or character. This can be used to control the tone and style of the output.

*   **Prompt:** The input given to a language model to elicit a response. A prompt can be a question, a command, a piece of text to complete, or any other form of input.

*   **Prompt Engineering:** The art and science of designing effective prompts to guide language models toward desired outputs.

*   **Prompt Injection:** A type of security attack where a user crafts a prompt to make an LLM ignore its original instructions and perform unintended actions.

### R

*   **Red Teaming:** A form of adversarial testing where a team of experts tries to find vulnerabilities and weaknesses in an AI system. This is a key practice for improving model safety and security.

*   **Reinforcement Learning from Human Feedback (RLHF):** A training technique where human feedback is used to fine-tune a language model to be more helpful, harmless, and aligned with human preferences.

*   **Retrieval-Augmented Generation (RAG):** A technique where an LLM is connected to an external knowledge base (such as a database or document collection) to retrieve relevant information before generating a response. This helps to improve factual accuracy and reduce hallucinations.

### S

*   **Stochastic:** Randomly determined. The outputs of LLMs are often stochastic, meaning that the same prompt can produce slightly different responses on different runs.

### T

*   **Temperature:** A parameter that controls the randomness of an LLM's output. Higher temperatures result in more creative and diverse responses, while lower temperatures produce more deterministic and focused outputs.

*   **Token:** A unit of text that a language model processes. A token can be a word, a part of a word, or a punctuation mark. The context window of an LLM is measured in tokens.

*   **Transformer:** A type of neural network architecture that is particularly well-suited for processing sequential data like text. Most modern LLMs are based on the transformer architecture.

### Z

*   **Zero-Shot Prompting:** A prompting technique where the model is asked to perform a task without any prior examples in the prompt. This relies on the model's general knowledge and instruction-following capabilities.

