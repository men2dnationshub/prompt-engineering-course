# Module 06: Evaluating Prompts and Outputs - Exercises

These exercises will help you develop critical skills in evaluating LLM performance, identifying issues, and systematically improving prompt effectiveness. Each exercise focuses on practical evaluation techniques you can apply in real-world scenarios.

## Exercise 1: Establishing Evaluation Metrics

### Task 1.1: Metric Framework Design

Design a comprehensive evaluation framework for a customer service chatbot.

**Application Context:** E-commerce customer service chatbot handling order inquiries, returns, and general questions.

**Your Evaluation Framework:**

**Quantitative Metrics:**
```
1. [Metric name]: [Description and measurement method]
2. [Metric name]: [Description and measurement method]
3. [Metric name]: [Description and measurement method]
4. [Metric name]: [Description and measurement method]
5. [Metric name]: [Description and measurement method]
```

**Qualitative Metrics:**
```
1. [Metric name]: [Description and assessment method]
2. [Metric name]: [Description and assessment method]
3. [Metric name]: [Description and assessment method]
```

**Example Solution:**
```
Quantitative Metrics:
1. Response Accuracy: Percentage of factually correct responses (measured against verified information)
2. Response Time: Average time to generate response (measured in seconds)
3. Resolution Rate: Percentage of inquiries resolved without escalation
4. User Satisfaction Score: Average rating from post-interaction surveys (1-5 scale)
5. Cost per Interaction: Computational cost per customer interaction

Qualitative Metrics:
1. Tone Appropriateness: Professional, empathetic tone suitable for customer service
2. Completeness: Responses address all aspects of customer inquiry
3. Clarity: Responses are easy to understand and well-structured
```

### Task 1.2: Domain-Specific Evaluation

Create evaluation criteria for a technical documentation generator.

**Application:** AI system that generates API documentation from code comments.

**Your Evaluation Criteria:**
```
Technical Accuracy: [How will you measure correctness?]
Completeness: [What elements must be included?]
Usability: [How will you assess user-friendliness?]
Consistency: [What standards must be maintained?]
```

---

## Exercise 2: Identifying LLM Issues

### Task 2.1: Hallucination Detection

Analyze these LLM outputs and identify potential hallucinations:

**Prompt:** "Explain the discovery of the Higgs boson particle."

**Output A:**
"The Higgs boson was discovered in 2012 at CERN's Large Hadron Collider by the ATLAS and CMS experiments. The discovery was announced on July 4, 2012, and confirmed the existence of the Higgs field, which gives mass to other particles. Peter Higgs and François Englert won the Nobel Prize in Physics in 2013 for their theoretical work predicting this particle."

**Output B:**
"The Higgs boson was discovered in 2011 at CERN by Dr. Sarah Mitchell using the revolutionary Quantum Resonance Detector. This discovery proved that particles can travel faster than light and led to the development of time travel technology in 2015. The particle was found to have a mass of exactly 125.3 GeV and glows with a distinctive blue light when observed."

**Your Analysis:**
```
Output A Issues: [List any factual errors or concerns]

Output B Issues: [List hallucinations and fabricated information]

Detection Strategies: [How could you systematically identify these issues?]
```

### Task 2.2: Bias Detection Exercise

Evaluate these outputs for potential bias:

**Prompt:** "Describe the qualities of a good leader."

**Output A:**
"A good leader should be decisive, confident, and assertive. He should command respect through strength and never show weakness. Leaders are naturally competitive and should dominate discussions to maintain authority. They typically have strong analytical skills and prefer logic over emotion in decision-making."

**Output B:**
"Effective leaders demonstrate a balance of confidence and humility. They listen actively to diverse perspectives, communicate clearly, and adapt their leadership style to different situations and team members. Good leaders show empathy, build trust, and empower others to contribute their best work. They make thoughtful decisions while remaining open to feedback and learning."

**Your Bias Analysis:**
```
Output A Biases: [Identify specific biases and problematic assumptions]

Output B Assessment: [Evaluate for more subtle biases]

Mitigation Strategies: [How could prompts be designed to reduce bias?]
```

---

## Exercise 3: Iterative Prompt Refinement

### Task 3.1: Systematic Improvement Process

Take this initial prompt and improve it through iterative refinement:

**Initial Prompt:** "Write a product description."

**Iteration 1 - Add Specificity:**
```
[Rewrite the prompt with more specific requirements]
```

**Iteration 2 - Add Context and Constraints:**
```
[Further refine with context and limitations]
```

**Iteration 3 - Add Examples and Format:**
```
[Include examples and format specifications]
```

**Iteration 4 - Add Quality Controls:**
```
[Include quality assurance elements]
```

**Example Solution for Iteration 1:**
```
Write a product description for a wireless Bluetooth speaker. The description should be 150-200 words, highlight key features, and appeal to music enthusiasts aged 25-40.
```

### Task 3.2: Performance-Based Refinement

You're refining a prompt for generating email responses. Based on these performance issues, improve the prompt:

**Current Prompt:** "Write a professional email response to the customer inquiry."

**Identified Issues:**
- Responses are too formal and robotic
- Missing personalization elements
- Doesn't address specific customer concerns
- No clear call-to-action

**Your Refined Prompt:**
```
[Write an improved prompt that addresses these issues]
```

**Refinement Rationale:**
```
[Explain how your changes address each identified issue]
```

---

## Exercise 4: A/B Testing Design

### Task 4.1: Test Design for Content Generation

Design an A/B test to compare two approaches for generating social media posts.

**Context:** Marketing team wants to test whether detailed prompts or simple prompts work better for social media content.

**Hypothesis:**
```
[State your hypothesis clearly]
```

**Test Design:**

**Version A (Control):**
```
[Write the control prompt]
```

**Version B (Treatment):**
```
[Write the treatment prompt]
```

**Success Metrics:**
```
Primary Metric: [Main measure of success]
Secondary Metrics: [Additional measures]
```

**Sample Size and Duration:**
```
[Specify testing parameters]
```

**Example Solution:**
```
Hypothesis: Detailed prompts with specific brand guidelines will generate social media posts with higher engagement rates than simple prompts.

Version A (Control): "Create a social media post about our new product launch."

Version B (Treatment): "Create a social media post about our new product launch. Use an enthusiastic but professional tone, include a call-to-action, mention key benefits (durability, affordability, eco-friendly), and end with relevant hashtags. Keep it under 280 characters for Twitter compatibility."

Primary Metric: Engagement rate (likes, shares, comments per post)
Secondary Metrics: Click-through rate, brand sentiment, time to create
```

### Task 4.2: Multi-Variable Testing

Design a test to evaluate multiple prompt elements simultaneously.

**Scenario:** Testing email subject line generation for different variables.

**Variables to Test:**
- Tone (formal vs. casual)
- Length (short vs. long)
- Personalization (generic vs. personalized)

**Your Test Matrix:**
```
[Create a 2x2x2 test matrix with 8 different prompt combinations]

Combination 1: [Formal + Short + Generic]
Combination 2: [Formal + Short + Personalized]
[Continue for all 8 combinations]
```

**Analysis Plan:**
```
[Explain how you'll analyze the results to understand which factors matter most]
```

---

## Exercise 5: Quality Assurance Framework

### Task 5.1: Automated QA System Design

Design an automated quality assurance system for a content generation application.

**Application:** Blog post generator for a technology company.

**Your QA System:**

**Automated Checks:**
```
1. [Check type]: [What it validates and how]
2. [Check type]: [What it validates and how]
3. [Check type]: [What it validates and how]
4. [Check type]: [What it validates and how]
5. [Check type]: [What it validates and how]
```

**Escalation Rules:**
```
[Define when content should be flagged for human review]
```

**Feedback Loop:**
```
[Explain how QA results improve future outputs]
```

**Example Solution:**
```
Automated Checks:
1. Length Validation: Ensures posts are 800-1200 words (automated word count)
2. Readability Score: Checks Flesch-Kincaid score is appropriate for target audience
3. SEO Optimization: Validates keyword density and meta description presence
4. Fact-Checking: Cross-references claims against authoritative tech sources
5. Brand Compliance: Checks for required brand terms and prohibited language

Escalation Rules:
- Any automated check failure triggers human review
- Posts about sensitive topics (privacy, security) require expert review
- New product mentions require marketing team approval
```

### Task 5.2: Human Review Process

Design a human review process for high-stakes content.

**Context:** Legal document summarization for law firm clients.

**Review Process Design:**
```
Stage 1: [Initial review criteria and reviewer qualifications]
Stage 2: [Secondary review process]
Stage 3: [Final approval process]

Quality Criteria: [Specific standards reviewers should apply]
Training Requirements: [What training do reviewers need?]
Documentation: [How are review decisions recorded?]
```

---

## Exercise 6: Issue Mitigation Strategies

### Task 6.1: Hallucination Prevention

Design strategies to prevent hallucinations in a medical information chatbot.

**High-Risk Scenario:** Chatbot providing general health information to patients.

**Prevention Strategies:**

**Prompt Design:**
```
[How will you design prompts to reduce hallucination risk?]
```

**Verification Systems:**
```
[What systems will verify information accuracy?]
```

**Uncertainty Handling:**
```
[How will the system handle uncertain or unknown information?]
```

**Fallback Mechanisms:**
```
[What happens when the system can't provide reliable information?]
```

### Task 6.2: Bias Mitigation Framework

Create a comprehensive bias mitigation strategy.

**Application:** Resume screening assistant for HR departments.

**Bias Mitigation Strategy:**

**Prevention (Prompt Design):**
```
[How will you design prompts to minimize bias?]
```

**Detection (Monitoring):**
```
[How will you monitor for biased outputs?]
```

**Correction (Response):**
```
[How will you handle biased outputs when detected?]
```

**Continuous Improvement:**
```
[How will you improve bias mitigation over time?]
```

---

## Exercise 7: Performance Monitoring

### Task 7.1: Dashboard Design

Design a monitoring dashboard for a prompt engineering team.

**Team Context:** 5-person team managing 20+ different prompts across various applications.

**Dashboard Components:**

**Real-Time Metrics:**
```
[What metrics need real-time monitoring?]
```

**Trend Analysis:**
```
[What trends should be tracked over time?]
```

**Alert Systems:**
```
[What conditions should trigger alerts?]
```

**Performance Comparisons:**
```
[How will you compare different prompts and versions?]
```

### Task 7.2: Incident Response Plan

Create an incident response plan for quality issues.

**Scenario:** Customer service chatbot starts providing incorrect information about return policies.

**Response Plan:**

**Detection:**
```
[How will the issue be detected?]
```

**Immediate Response:**
```
[What immediate actions will be taken?]
```

**Investigation:**
```
[How will you determine the root cause?]
```

**Resolution:**
```
[How will you fix the issue?]
```

**Prevention:**
```
[How will you prevent similar issues in the future?]
```

---

## Exercise 8: Comprehensive Evaluation Project

### Task: Complete Evaluation System

Design a comprehensive evaluation system for a multi-purpose AI writing assistant.

**Application Features:**
- Email composition
- Report writing
- Creative writing
- Technical documentation
- Social media content

**Your Comprehensive System:**

**Evaluation Framework:**
```
[Design metrics and criteria for each content type]
```

**Testing Strategy:**
```
[Plan for systematic testing and improvement]
```

**Quality Assurance:**
```
[Design QA processes for different content types]
```

**Monitoring and Alerting:**
```
[Create monitoring system for ongoing operations]
```

**Continuous Improvement:**
```
[Plan for long-term improvement and learning]
```

**Resource Requirements:**
```
[Estimate human and technical resources needed]
```

---

## Reflection and Analysis

After completing these exercises:

1. **Evaluation Complexity:** Which aspects of evaluation were most challenging? Why?

2. **Issue Identification:** What patterns did you notice in common LLM issues?

3. **Mitigation Effectiveness:** Which mitigation strategies seem most practical and effective?

4. **Resource Trade-offs:** How do you balance thorough evaluation with resource constraints?

5. **Continuous Improvement:** What would be your priorities for building an evaluation culture in a team?

## Advanced Practice

- Implement one of your evaluation frameworks using real LLM outputs
- Create automated tools for bias detection or fact-checking
- Design and run an actual A/B test comparing prompt variations
- Build a monitoring dashboard for tracking prompt performance
- Develop training materials for teaching evaluation skills to others

