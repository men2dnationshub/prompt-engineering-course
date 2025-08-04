# Module 04: Advanced Prompting Techniques - Exercises

These exercises will help you master advanced prompting techniques that enhance LLM reasoning and output quality. Each exercise focuses on a specific technique and provides opportunities to practice and refine your skills.

## Exercise 1: Chain-of-Thought Prompting

### Task 1.1: Mathematical Problem Solving

Create a Chain-of-Thought prompt for solving this word problem:

**Problem:** "A company's revenue increased by 15% in the first quarter, decreased by 8% in the second quarter, and increased by 22% in the third quarter. If the revenue at the end of the third quarter was $2,484,000, what was the original revenue at the beginning of the first quarter?"

**Your Chain-of-Thought Prompt:**
```
[Write your prompt here, ensuring it guides step-by-step reasoning]
```

**Example Solution:**
```
Let's solve this step-by-step by working backwards from the final revenue:

1. Define variables and what we know:
   - Final revenue (end of Q3): $2,484,000
   - Q1: +15% increase
   - Q2: -8% decrease  
   - Q3: +22% increase
   - Need to find: Original revenue (beginning of Q1)

2. Set up the equation working backwards:
   - If original revenue = x
   - After Q1: x × 1.15
   - After Q2: x × 1.15 × 0.92
   - After Q3: x × 1.15 × 0.92 × 1.22 = $2,484,000

3. Calculate the combined multiplier:
   - 1.15 × 0.92 × 1.22 = 1.289

4. Solve for x:
   - x × 1.289 = $2,484,000
   - x = $2,484,000 ÷ 1.289
   - x = $1,927,000

Therefore, the original revenue was $1,927,000.
```

### Task 1.2: Logical Reasoning

Create a Chain-of-Thought prompt for this logic puzzle:

**Problem:** "In a building with 5 floors, each floor has a different colored door (red, blue, green, yellow, white). The red door is above the blue door. The green door is not on the top floor. The yellow door is exactly two floors below the white door. The blue door is on an odd-numbered floor. What color is the door on each floor?"

**Your Chain-of-Thought Prompt:**
```
[Write your prompt here]
```

---

## Exercise 2: Self-Consistency Prompting

### Task 2.1: Multiple Perspective Analysis

Create a self-consistency prompt for analyzing this business decision:

**Scenario:** "A small restaurant owner is deciding whether to expand to a second location or invest in upgrading the current location with new equipment and renovations."

**Your Self-Consistency Prompt:**
```
[Write your prompt that explores multiple analytical approaches]
```

**Requirements:**
- Analyze from at least 3 different perspectives (financial, operational, strategic)
- Identify consistent themes across analyses
- Provide a synthesized recommendation

### Task 2.2: Problem-Solving Validation

Create a self-consistency prompt for this technical problem:

**Problem:** "A website is experiencing slow loading times. Users report that pages take 8-12 seconds to load, but the development team's tests show 2-3 second load times."

**Your Self-Consistency Prompt:**
```
[Write your prompt that uses multiple diagnostic approaches]
```

---

## Exercise 3: Reflexion and Iterative Prompting

### Task 3.1: Content Improvement

Create a reflexion prompt for improving written content:

**Initial Content:** "Artificial intelligence is changing business. Companies use AI for many things. It helps with efficiency and decision making. AI can analyze data quickly. This saves time and money."

**Your Reflexion Prompt:**
```
[Write your two-stage prompt: initial improvement + reflection]
```

**Requirements:**
- First stage: Improve the content
- Second stage: Reflect on improvements and refine further
- Focus on clarity, engagement, and informativeness

### Task 3.2: Code Review and Improvement

Create a reflexion prompt for code improvement:

**Initial Code:**
```python
def calculate_total(items):
    total = 0
    for item in items:
        total = total + item['price'] * item['quantity']
    return total
```

**Your Reflexion Prompt:**
```
[Write your prompt for code review and improvement]
```

**Focus Areas:**
- Error handling
- Code efficiency
- Documentation
- Best practices

---

## Exercise 4: Tree of Thought Prompting

### Task 4.1: Strategic Planning

Create a Tree of Thought prompt for this strategic challenge:

**Challenge:** "A mid-sized software company needs to decide how to respond to a new competitor that's offering similar services at 30% lower prices."

**Your Tree of Thought Prompt:**
```
[Write your prompt that explores multiple strategic branches]
```

**Required Branches:**
- Competitive pricing strategy
- Differentiation strategy
- Innovation/new product strategy
- Market positioning strategy

### Task 4.2: Creative Problem Solving

Create a Tree of Thought prompt for this design challenge:

**Challenge:** "Design a mobile app feature that helps remote workers maintain better work-life balance."

**Your Tree of Thought Prompt:**
```
[Write your prompt exploring different design approaches]
```

**Exploration Areas:**
- Time management features
- Communication boundaries
- Wellness integration
- Productivity optimization

---

## Exercise 5: Priming and Context Setting

### Task 5.1: Expert Persona Priming

Create priming prompts for the same question from different expert perspectives:

**Question:** "How can a company improve employee retention?"

**Prompt 1 - HR Director Perspective:**
```
[Write your primed prompt]
```

**Prompt 2 - Financial Analyst Perspective:**
```
[Write your primed prompt]
```

**Prompt 3 - Organizational Psychologist Perspective:**
```
[Write your primed prompt]
```

### Task 5.2: Audience-Specific Priming

Create priming prompts to explain the same concept to different audiences:

**Concept:** "Blockchain technology"

**Prompt 1 - For Elementary School Students:**
```
[Write your primed prompt]
```

**Prompt 2 - For Business Executives:**
```
[Write your primed prompt]
```

**Prompt 3 - For Technical Developers:**
```
[Write your primed prompt]
```

---

## Exercise 6: Combining Advanced Techniques

### Task 6.1: Comprehensive Analysis

Create a prompt that combines multiple advanced techniques for this complex scenario:

**Scenario:** "A university is considering implementing a new online learning platform. They need to evaluate the decision from multiple angles, ensure thorough analysis, and arrive at a well-reasoned recommendation."

**Your Combined Technique Prompt:**
```
[Write your comprehensive prompt using multiple techniques]
```

**Required Elements:**
- Priming (establish expert perspective)
- Tree of Thought (explore multiple evaluation criteria)
- Chain-of-Thought (detailed reasoning for each criterion)
- Self-Consistency (cross-validate findings)
- Reflexion (review and improve the analysis)

### Task 6.2: Creative Project Development

Create a combined technique prompt for this creative challenge:

**Challenge:** "Develop a concept for a new podcast series that would appeal to young professionals interested in career development."

**Your Combined Prompt:**
```
[Write your prompt combining multiple techniques]
```

**Technique Integration:**
- Priming for creative expertise
- Tree of Thought for concept exploration
- Reflexion for concept refinement
- Chain-of-Thought for detailed development

---

## Exercise 7: Technique Selection and Optimization

### Task 7.1: Technique Matching

For each scenario below, identify which advanced technique(s) would be most appropriate and explain why:

**Scenario A:** Debugging a complex software issue with multiple potential causes
**Best Technique(s):** _______________
**Reasoning:** _______________

**Scenario B:** Writing a comprehensive research report on climate change impacts
**Best Technique(s):** _______________
**Reasoning:** _______________

**Scenario C:** Developing a marketing campaign for a new product
**Best Technique(s):** _______________
**Reasoning:** _______________

**Scenario D:** Solving a complex mathematical optimization problem
**Best Technique(s):** _______________
**Reasoning:** _______________

### Task 7.2: Prompt Evolution

Take this basic prompt and evolve it using advanced techniques:

**Basic Prompt:** "Help me plan a team building event for my company."

**Evolution 1 - Add Chain-of-Thought:**
```
[Rewrite with step-by-step reasoning]
```

**Evolution 2 - Add Priming:**
```
[Add expert perspective and context]
```

**Evolution 3 - Add Tree of Thought:**
```
[Explore multiple planning approaches]
```

**Evolution 4 - Add Reflexion:**
```
[Include review and improvement cycle]
```

---

## Challenge Exercise: Master Integration

### Task: Advanced Technique Showcase

Choose a real-world problem from your professional or academic life and create a comprehensive prompt solution that demonstrates mastery of multiple advanced techniques.

**Your Problem:**
```
[Describe your chosen problem]
```

**Your Master Prompt:**
```
[Write your comprehensive solution using multiple advanced techniques]
```

**Technique Documentation:**
```
Techniques Used:
1. [Technique name]: [How and why you used it]
2. [Technique name]: [How and why you used it]
3. [Continue as needed]

Expected Benefits:
[Explain how each technique contributes to better outcomes]
```

---

## Reflection and Analysis

After completing these exercises:

1. **Technique Effectiveness:** Which advanced technique felt most natural to implement? Which was most challenging?

2. **Quality Improvement:** How did the advanced techniques change the quality of responses compared to basic prompting?

3. **Combination Synergy:** When combining techniques, which combinations worked best together? Were there any conflicts?

4. **Practical Application:** Which techniques do you see yourself using most frequently in real-world scenarios?

5. **Learning Insights:** What surprised you most about these advanced techniques?

## Next Steps

- Practice applying these techniques to your daily LLM interactions
- Experiment with different combinations for various problem types
- Start building a personal library of advanced prompt templates
- Begin developing your own variations and improvements on these techniques

