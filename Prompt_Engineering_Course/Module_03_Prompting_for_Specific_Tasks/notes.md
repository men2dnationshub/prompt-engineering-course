# Module 03: Prompting for Specific Tasks

## 3.1 Text Generation Tasks

Text generation is one of the most versatile applications of Large Language Models. This broad category encompasses creative writing, content creation, summarization, translation, and many other language-related tasks. Each type of text generation requires specific prompting strategies to achieve optimal results.

### Creative Writing

Creative writing prompts should inspire the LLM while providing enough structure to guide the creative process. The key is balancing creative freedom with specific requirements.

**Essential Elements for Creative Writing Prompts:**

*   **Genre and Style Specification:** Clearly indicate the type of creative work you want (short story, poem, dialogue, etc.) and any specific style requirements.
*   **Setting and Context:** Provide background information, time period, location, or thematic elements.
*   **Character Guidelines:** If applicable, describe main characters, their relationships, or personality traits.
*   **Tone and Mood:** Specify the emotional atmosphere you want to create.
*   **Length and Structure:** Define the scope and format of the creative piece.

**Example Creative Writing Prompt:**
```
Write a 500-word short story in the style of magical realism. The story should be set in a small coastal town where the lighthouse keeper discovers that the lighthouse beam can illuminate memories from the past. The tone should be nostalgic and slightly melancholic. Include dialogue between the lighthouse keeper and a mysterious visitor who appears only when the beam reveals certain memories.
```

### Content Summarization

Summarization requires the LLM to distill complex information into concise, coherent summaries while preserving the most important points. Effective summarization prompts must specify the level of detail, target audience, and format requirements.

**Key Considerations for Summarization Prompts:**

*   **Source Material Handling:** Use clear delimiters to separate the text to be summarized from the instructions.
*   **Length Specifications:** Define the desired length (word count, sentence count, or paragraph count).
*   **Focus Areas:** Indicate which aspects of the content should be emphasized.
*   **Audience Consideration:** Specify who will read the summary to guide the appropriate level of technical detail.
*   **Format Requirements:** Determine whether you want bullet points, paragraphs, or other specific formats.

**Example Summarization Prompt:**
```
Summarize the following research article in 200 words for a general audience with no scientific background. Focus on the main findings, practical implications, and why this research matters to everyday people. Use clear, jargon-free language and organize the summary into three paragraphs: 1) What the study found, 2) How it was conducted, 3) What it means for the average person.

[Article text here]
```

### Translation and Language Tasks

While LLMs are not replacement for professional translation services, they can be effective for basic translation tasks and language-related activities. Translation prompts should consider cultural context, formality levels, and specific linguistic requirements.

**Important Aspects of Translation Prompts:**

*   **Source and Target Languages:** Clearly specify both languages involved.
*   **Context and Domain:** Provide information about the subject matter or field.
*   **Formality Level:** Indicate whether the translation should be formal, informal, or match the original tone.
*   **Cultural Considerations:** Note any cultural adaptations that might be necessary.
*   **Quality Expectations:** Specify whether you need a rough translation or something more polished.

**Example Translation Prompt:**
```
Translate the following business email from English to Spanish. Maintain a professional, formal tone appropriate for corporate communication. Ensure that cultural business etiquette is respected in the Spanish version.

[Email text here]

Please also provide a brief note explaining any cultural adaptations you made in the translation.
```

## 3.2 Question Answering

Question answering is a fundamental application of LLMs that requires careful prompt design to ensure accurate, relevant, and appropriately detailed responses. The effectiveness of Q&A prompts depends on how well they frame the question and provide necessary context.

### Types of Question Answering

**Factual Questions:** These seek specific, verifiable information. Prompts should be direct and may benefit from requesting sources or confidence levels.

**Analytical Questions:** These require interpretation, analysis, or reasoning. Prompts should provide sufficient context and may request step-by-step reasoning.

**Opinion-Based Questions:** These seek perspectives or recommendations. Prompts should clarify the desired viewpoint and any relevant constraints.

**Comparative Questions:** These ask for comparisons between options. Prompts should specify comparison criteria and desired format.

### Strategies for Effective Q&A Prompts

**Provide Sufficient Context:** Include background information that helps the LLM understand the scope and purpose of the question.

**Specify Answer Format:** Indicate whether you want a brief answer, detailed explanation, bullet points, or other specific formats.

**Request Evidence or Reasoning:** For complex questions, ask the LLM to explain its reasoning or provide supporting evidence.

**Set Boundaries:** Clarify what aspects of the topic you want covered and what should be excluded.

**Example Q&A Prompt:**
```
I'm a small business owner considering whether to implement a remote work policy for my 15-person marketing agency. Based on current research and best practices, what are the main advantages and disadvantages of remote work for creative teams? Please provide:

1. Three key benefits with brief explanations
2. Three potential challenges with suggested mitigation strategies
3. Factors specific to marketing agencies that I should consider
4. A recommendation for a gradual implementation approach

Please base your response on established business research and clearly indicate when you're providing general guidance versus specific recommendations.
```

## 3.3 Code Generation and Explanation

LLMs have demonstrated remarkable capabilities in understanding, generating, and explaining code across multiple programming languages. Effective code-related prompts require clear specifications about the programming language, functionality requirements, and code quality expectations.

### Code Generation Prompts

When requesting code generation, specificity is crucial for getting functional, efficient code that meets your requirements.

**Essential Elements for Code Generation Prompts:**

*   **Programming Language:** Specify the exact language and version if relevant.
*   **Functionality Description:** Clearly describe what the code should accomplish.
*   **Input/Output Specifications:** Define expected inputs and desired outputs.
*   **Constraints and Requirements:** Include performance requirements, coding standards, or limitations.
*   **Context and Environment:** Provide information about the broader system or framework.

**Example Code Generation Prompt:**
```
Write a Python function that takes a list of dictionaries representing students (each with 'name', 'age', and 'grades' keys where 'grades' is a list of numbers) and returns a new list containing only students whose average grade is above 85. The function should:

1. Handle empty lists gracefully
2. Skip students with no grades
3. Include proper error handling for invalid data types
4. Include docstring documentation
5. Follow PEP 8 style guidelines

Please also provide a few test cases demonstrating the function's usage.
```

### Code Explanation Prompts

When asking for code explanations, specify the level of detail and target audience to get appropriately tailored explanations.

**Example Code Explanation Prompt:**
```
Explain the following Python code to someone who is new to programming. Break down each line, explain the logic flow, and describe what the overall function accomplishes. Use simple language and provide analogies where helpful.

[Code block here]

Please organize your explanation with:
1. Overall purpose of the function
2. Line-by-line breakdown
3. Example of how it would work with sample input
4. Key programming concepts demonstrated
```

## 3.4 Data Extraction and Formatting

LLMs excel at extracting structured information from unstructured text and reformatting data into desired formats. This capability is particularly valuable for processing documents, parsing information, and organizing data.

### Information Extraction

Effective data extraction prompts clearly define what information to extract and how to handle edge cases or missing data.

**Key Components of Extraction Prompts:**

*   **Source Material:** Clearly delimit the text to be processed.
*   **Target Information:** Specify exactly what data points to extract.
*   **Output Format:** Define the structure for presenting extracted information.
*   **Handling Missing Data:** Indicate how to handle cases where requested information isn't available.
*   **Validation Requirements:** Specify any data validation or formatting requirements.

**Example Data Extraction Prompt:**
```
Extract the following information from the job posting below and format it as a JSON object:

- Job title
- Company name
- Location (city, state/country)
- Salary range (if mentioned)
- Required experience level
- Key skills/qualifications (list up to 5)
- Application deadline (if mentioned)

If any information is not available, use "Not specified" as the value. For salary, if only one figure is mentioned, put it in both min and max fields.

[Job posting text here]

Format the output as valid JSON with appropriate field names.
```

### Data Formatting and Transformation

LLMs can effectively transform data from one format to another, such as converting tables to different structures or reformatting text data.

**Example Data Formatting Prompt:**
```
Convert the following unstructured product information into a standardized format suitable for an e-commerce database. Create a consistent structure with the following fields: product_name, category, price, description, features (as a list), and availability_status.

[Unstructured product descriptions here]

Output each product as a separate JSON object, ensuring consistent formatting and data types across all entries.
```

## 3.5 Best Practices for Task-Specific Prompting

### Understanding Task Requirements

Before crafting a prompt, thoroughly understand the specific requirements and constraints of your task. Consider the intended audience, quality standards, and how the output will be used.

### Iterative Refinement

Start with a basic prompt and refine it based on the outputs you receive. Pay attention to common issues or areas where the LLM consistently misunderstands your requirements.

### Template Development

For recurring tasks, develop prompt templates that can be easily adapted for different inputs while maintaining consistent quality and format.

### Quality Validation

Establish methods for validating the quality of outputs, especially for critical applications. This might include fact-checking, code testing, or human review processes.

### Handling Limitations

Be aware of LLM limitations for specific tasks and design prompts that work within these constraints. For example, acknowledge knowledge cutoff dates for factual questions or computational limitations for complex calculations.

By mastering these task-specific prompting techniques, you'll be able to leverage LLMs effectively across a wide range of applications, from creative endeavors to technical tasks and data processing challenges.

