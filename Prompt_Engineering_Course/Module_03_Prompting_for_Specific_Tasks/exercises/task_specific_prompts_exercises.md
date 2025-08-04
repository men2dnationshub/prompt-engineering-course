# Module 03: Prompting for Specific Tasks - Exercises

These exercises will help you practice applying prompt engineering techniques to common LLM use cases. Each exercise focuses on a different type of task and includes multiple scenarios to build your skills.

## Exercise 1: Creative Writing Prompts

### Task 1.1: Short Story Generation

Create a prompt for generating a short story with specific requirements:

**Your Prompt:**
```
[Write your creative writing prompt here]
```

**Requirements to Include:**
- Genre: Science fiction
- Setting: Space station in the year 2150
- Main character: A maintenance engineer who discovers something unexpected
- Tone: Suspenseful but hopeful
- Length: 400-500 words
- Include dialogue

**Example Solution:**
```
Write a 400-500 word science fiction short story set on a space station in the year 2150. The protagonist is a maintenance engineer who discovers something unexpected during a routine repair. The tone should be suspenseful but ultimately hopeful. Include dialogue between the engineer and at least one other character. Focus on building tension through the discovery and resolution through human ingenuity and cooperation.
```

### Task 1.2: Poetry Creation

Create a prompt for generating a specific type of poem:

**Your Prompt:**
```
[Write your poetry prompt here]
```

**Requirements:**
- Type: Haiku series (3 haikus)
- Theme: Seasons changing
- Mood: Reflective and peaceful
- Include nature imagery

---

## Exercise 2: Summarization Tasks

### Task 2.1: Article Summarization

Create a prompt for summarizing a technical article for different audiences:

**Scenario:** You have a research article about renewable energy technology that needs to be summarized for a company newsletter.

**Your Prompt:**
```
[Write your summarization prompt here]
```

**Requirements:**
- Target audience: General employees (non-technical)
- Length: 150 words
- Focus on practical implications
- Include key statistics
- Use accessible language

### Task 2.2: Meeting Notes Summary

Create a prompt for summarizing meeting notes:

**Your Prompt:**
```
[Write your meeting summary prompt here]
```

**Requirements:**
- Extract action items
- Identify key decisions
- Note unresolved issues
- Format as bullet points
- Include responsible parties and deadlines

---

## Exercise 3: Question Answering

### Task 3.1: Comparative Analysis

Create a prompt that asks for a comparison between options:

**Scenario:** You're deciding between different project management methodologies for your team.

**Your Prompt:**
```
[Write your comparative Q&A prompt here]
```

**Requirements:**
- Compare Agile vs. Waterfall methodologies
- Consider team size (8 people)
- Project type (software development)
- Include pros/cons for each
- Provide a recommendation with reasoning

### Task 3.2: Troubleshooting Question

Create a prompt for getting help with a technical problem:

**Your Prompt:**
```
[Write your troubleshooting prompt here]
```

**Scenario:**
- Problem: Website loading slowly
- Context: E-commerce site with 1000+ daily visitors
- Recent changes: Added new product images
- Request step-by-step diagnostic approach

---

## Exercise 4: Code Generation

### Task 4.1: Function Creation

Create a prompt for generating a specific function:

**Your Prompt:**
```
[Write your code generation prompt here]
```

**Requirements:**
- Language: Python
- Function: Calculate compound interest
- Inputs: principal, rate, time, compounding frequency
- Include error handling
- Add documentation
- Provide usage examples

### Task 4.2: Code Explanation

Create a prompt for explaining existing code:

**Sample Code to Explain:**
```python
def fibonacci(n):
    if n <= 1:
        return n
    else:
        return fibonacci(n-1) + fibonacci(n-2)
```

**Your Explanation Prompt:**
```
[Write your code explanation prompt here]
```

**Requirements:**
- Target audience: Programming beginners
- Explain recursion concept
- Discuss efficiency considerations
- Provide step-by-step walkthrough

---

## Exercise 5: Data Extraction

### Task 5.1: Contact Information Extraction

Create a prompt for extracting contact information from business cards or emails:

**Sample Text:**
```
John Smith, Senior Marketing Manager at TechCorp Solutions, can be reached at j.smith@techcorp.com or by phone at (555) 123-4567. Our office is located at 123 Business Ave, Suite 200, New York, NY 10001. Feel free to connect with me on LinkedIn at linkedin.com/in/johnsmith-marketing.
```

**Your Extraction Prompt:**
```
[Write your data extraction prompt here]
```

**Required Fields:**
- Name
- Title
- Company
- Email
- Phone
- Address
- Social media profiles

### Task 5.2: Product Information Extraction

Create a prompt for extracting structured product data:

**Sample Product Description:**
```
The UltraBook Pro 15 is a high-performance laptop featuring an Intel Core i7 processor, 16GB RAM, and 512GB SSD storage. With a 15.6-inch 4K display and up to 12 hours of battery life, it's perfect for professionals on the go. Available in Space Gray and Silver for $1,299. Ships within 2-3 business days.
```

**Your Extraction Prompt:**
```
[Write your product extraction prompt here]
```

**Required Output Format:** JSON with fields for name, specs, price, colors, shipping time

---

## Exercise 6: Multi-Task Combination

### Task 6.1: Content Creation Pipeline

Create a comprehensive prompt that combines multiple tasks:

**Scenario:** You need to create a blog post about a new product launch.

**Your Multi-Task Prompt:**
```
[Write your comprehensive prompt here]
```

**Requirements:**
- Research and summarize key product features
- Write an engaging introduction
- Create bullet points for main benefits
- Generate a call-to-action
- Suggest social media post variations
- Target audience: Tech-savvy consumers
- Tone: Enthusiastic but informative

---

## Exercise 7: Prompt Optimization

### Task 7.1: Iterative Improvement

Take one of your prompts from the previous exercises and create three improved versions:

**Original Prompt:**
```
[Choose one of your previous prompts]
```

**Improved Version 1 (Focus: Clarity):**
```
[Rewrite focusing on clearer instructions]
```

**Improved Version 2 (Focus: Specificity):**
```
[Rewrite with more specific requirements]
```

**Improved Version 3 (Focus: Structure):**
```
[Rewrite with better organization and formatting]
```

**Reflection:** What specific changes did you make in each version and why?

---

## Challenge Exercise: Real-World Application

### Task: Create a Prompt Suite

Choose a real scenario from your work, studies, or personal projects and create a suite of 3-5 related prompts that would help you accomplish a larger goal.

**Example Scenario:** Planning a small business launch

**Prompt Suite:**
1. Market research and competitor analysis
2. Business plan outline generation
3. Marketing strategy development
4. Financial projections formatting
5. Pitch deck content creation

**Your Scenario:**
```
[Describe your chosen scenario]
```

**Your Prompt Suite:**
```
Prompt 1: [Title and prompt]

Prompt 2: [Title and prompt]

Prompt 3: [Title and prompt]

[Continue as needed]
```

---

## Reflection Questions

After completing these exercises:

1. Which type of task felt most challenging to prompt for? Why?
2. How did your approach differ between creative tasks and analytical tasks?
3. What patterns did you notice in your most effective prompts?
4. How important was output format specification for different task types?
5. What would you do differently if you were to repeat these exercises?

## Next Steps

- Apply these techniques to your own real-world tasks
- Experiment with combining different task types in single prompts
- Start building a personal library of effective prompt templates
- Practice iterating and improving prompts based on outputs received

