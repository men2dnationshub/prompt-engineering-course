# Module 02: Basic Prompting Techniques

## 2.1 Anatomy of a Good Prompt

A well-crafted prompt is the foundation of effective interaction with Large Language Models. Understanding the components that make up a good prompt is essential for achieving desired outcomes. A good prompt typically includes several key elements:

### Context and Background

Providing context helps the LLM understand the situation or domain in which it should operate. This might include background information, the purpose of the task, or the intended audience for the output. For example, if you're asking for a business plan, providing context about the industry, target market, or company size can significantly improve the relevance of the response.

### Clear Instructions

The core of any prompt is the instruction or task you want the LLM to perform. This should be stated clearly and unambiguously. Vague instructions often lead to vague or irrelevant outputs. Instead of saying "write something about dogs," a clearer instruction would be "write a 200-word informative paragraph about the benefits of dog ownership for families with children."

### Constraints and Parameters

Specifying constraints helps guide the LLM's output to meet your specific requirements. These might include:

*   Length requirements (word count, number of paragraphs)
*   Format specifications (bullet points, numbered lists, essay format)
*   Tone and style guidelines (formal, casual, humorous, professional)
*   Content restrictions (avoid certain topics, include specific information)

### Examples (When Appropriate)

Providing examples of the desired output format or style can be incredibly helpful, especially for complex or nuanced tasks. This technique, known as few-shot prompting, will be covered in detail later in this module.

### Output Format Specification

Clearly stating how you want the output formatted can save time and ensure consistency. This might include requesting specific structures like JSON format for data, markdown for documentation, or particular heading styles for reports.

## 2.2 Clarity and Specificity in Prompts

The principle of clarity and specificity is fundamental to effective prompt engineering. LLMs perform best when they receive precise, unambiguous instructions that leave little room for misinterpretation.

### The Importance of Precision

Ambiguous prompts often result in outputs that miss the mark. Consider the difference between these two prompts:

**Vague:** "Tell me about marketing."
**Specific:** "Explain three digital marketing strategies that small businesses can use to increase online sales, including specific tactics and expected outcomes for each strategy."

The specific prompt provides clear direction about the scope (digital marketing), target audience (small businesses), goal (increase online sales), required structure (three strategies), and level of detail (specific tactics and outcomes).

### Avoiding Assumptions

LLMs don't have access to your thoughts or unstated assumptions. What seems obvious to you may not be clear to the model. Always explicitly state important details rather than assuming the LLM will infer them correctly.

### Using Precise Language

Choose words that convey exactly what you mean. Technical terms, when used correctly, can provide precision, but ensure they're appropriate for the context. Similarly, be specific about quantities, timeframes, and other measurable elements.

## 2.3 Zero-Shot Prompting

Zero-shot prompting refers to asking an LLM to perform a task without providing any examples of the desired output. This relies entirely on the model's pre-trained knowledge and its ability to understand and follow instructions.

### When to Use Zero-Shot Prompting

Zero-shot prompting is effective for:

*   Simple, well-defined tasks
*   Tasks that the LLM has likely encountered during training
*   Situations where you want to see the model's "natural" approach to a problem
*   Quick, one-off requests

### Characteristics of Effective Zero-Shot Prompts

Successful zero-shot prompts typically:

*   Use clear, direct language
*   Specify the desired output format
*   Include relevant context
*   Set appropriate constraints

### Example of Zero-Shot Prompting

**Prompt:** "Write a professional email declining a job offer. The email should be polite, express gratitude for the opportunity, and maintain a positive relationship with the company."

This prompt provides clear instructions without examples, relying on the LLM's understanding of professional communication norms.

## 2.4 Few-Shot Prompting (In-Context Learning)

Few-shot prompting involves providing one or more examples of the desired input-output pattern before asking the LLM to perform the task. This technique leverages the model's ability to learn from context and apply patterns to new situations.

### The Power of Examples

Examples serve multiple purposes:

*   They clarify the expected output format
*   They demonstrate the level of detail required
*   They show the style and tone you're looking for
*   They help the LLM understand complex or nuanced tasks

### Structure of Few-Shot Prompts

A typical few-shot prompt follows this pattern:

1.  Task description (optional but helpful)
2.  Example 1: Input → Output
3.  Example 2: Input → Output
4.  (Additional examples as needed)
5.  New input for the LLM to process

### Example of Few-Shot Prompting

**Prompt:**
```
Classify the sentiment of the following movie reviews as positive, negative, or neutral.

Review: "This movie was absolutely fantastic! The acting was superb and the plot kept me engaged throughout."
Sentiment: Positive

Review: "The movie was okay. Nothing special, but not terrible either."
Sentiment: Neutral

Review: "I hated this film. The dialogue was terrible and the story made no sense."
Sentiment: Negative

Review: "An incredible cinematic experience with breathtaking visuals and outstanding performances."
Sentiment:
```

### Choosing the Right Number of Examples

The optimal number of examples depends on:

*   Task complexity
*   Consistency of the pattern
*   LLM's familiarity with the task type
*   Token limitations

Generally, 1-5 examples are sufficient for most tasks, though some complex scenarios might benefit from more.

## 2.5 Role-Playing in Prompts

Role-playing is a powerful technique where you ask the LLM to adopt a specific persona, profession, or character when responding. This can significantly influence the tone, style, expertise level, and perspective of the output.

### Benefits of Role-Playing

*   **Expertise Simulation:** You can access specialized knowledge by having the LLM role-play as an expert in a particular field.
*   **Tone Control:** Different roles naturally produce different communication styles.
*   **Perspective Diversity:** Role-playing can help you see problems from different viewpoints.
*   **Engagement:** It can make interactions more engaging and creative.

### Effective Role-Playing Techniques

When implementing role-playing:

*   Be specific about the role and its characteristics
*   Provide context about the role's expertise and background
*   Set expectations for how the role should behave
*   Consider the role's likely knowledge limitations

### Examples of Role-Playing

**Example 1: Expert Consultant**
"Act as a senior financial advisor with 20 years of experience helping small businesses. Provide advice on..."

**Example 2: Creative Character**
"Respond as a wise old wizard who speaks in riddles and metaphors. Answer this question about..."

**Example 3: Specific Professional**
"You are a pediatric nurse with extensive experience in child development. Explain to a concerned parent..."

## 2.6 Using Delimiters

Delimiters are special characters or symbols used to clearly separate different parts of a prompt, particularly when including text that the LLM should process rather than interpret as instructions.

### Common Delimiter Types

*   **Triple quotes:** ```text to process```
*   **XML-style tags:** `<text>content</text>`
*   **Brackets:** `[text to analyze]`
*   **Dashes or asterisks:** `---text---` or `***text***`

### Why Delimiters Matter

Delimiters help prevent:

*   **Prompt injection:** Where user input might be interpreted as instructions
*   **Confusion:** Between instructions and content to be processed
*   **Formatting issues:** Ensuring proper separation of different prompt components

### Example Using Delimiters

**Prompt:**
```
Analyze the sentiment of the following customer review and provide a brief explanation:

"""
I bought this product last week and I'm really disappointed. The quality is much worse than advertised and it broke after just two days of use. I would not recommend this to anyone.
"""

Provide your analysis in the following format:
- Sentiment: [Positive/Negative/Neutral]
- Confidence: [High/Medium/Low]
- Key indicators: [List main words/phrases that influenced your decision]
```

The triple quotes clearly separate the review text from the instructions, ensuring the LLM understands what to analyze versus what instructions to follow.

## 2.7 Best Practices for Basic Prompting

As you begin your journey in prompt engineering, keep these fundamental best practices in mind:

### Start Simple, Then Iterate

Begin with straightforward prompts and gradually add complexity as needed. This approach helps you understand what works and makes it easier to identify issues when they arise.

### Be Explicit About Requirements

Don't assume the LLM will infer your preferences. Explicitly state requirements for length, format, tone, and content.

### Test and Refine

Prompt engineering is an iterative process. Test your prompts, analyze the outputs, and refine your approach based on the results.

### Consider the Model's Perspective

Think about how the LLM might interpret your prompt. What ambiguities exist? What assumptions might it make?

### Document Successful Patterns

Keep track of prompts that work well for specific types of tasks. Building a personal library of effective prompt patterns will save time and improve consistency.

### Understand Limitations

Remember that LLMs have limitations in terms of knowledge cutoffs, reasoning capabilities, and potential biases. Design your prompts with these limitations in mind.

By mastering these basic prompting techniques, you'll have a solid foundation for more advanced prompt engineering strategies covered in subsequent modules.

