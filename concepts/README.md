<div align="center">

# 🧠 Core Concepts in Prompt Engineering

<p align="center">
  <img src="https://img.shields.io/badge/Concepts-7_Core_Ideas-blue?style=for-the-badge&logo=brain" alt="7 Core Concepts"/>
  <img src="https://img.shields.io/badge/Difficulty-Intermediate-orange?style=for-the-badge" alt="Intermediate"/>
  <img src="https://img.shields.io/badge/Reading_Time-20_minutes-green?style=for-the-badge&logo=clock" alt="20 Minutes"/>
</p>

<p align="center">
  <strong>Master the fundamental concepts that make prompts work</strong><br/>
  Simple analogies and practical examples for deep understanding
</p>

</div>

---

## 🗺️ Concept Navigation

<div align="center">

### Choose Your Learning Focus

</div>

<table>
<tr>
<td align="center" width="25%">

**📝 Context & Clarity**

<a href="#context-and-specificity">
<img src="https://img.shields.io/badge/Learn_Context-Essential-FF6B6B?style=for-the-badge" alt="Context"/>
</a>

*Make prompts crystal clear*

</td>
<td align="center" width="25%">

**🔗 Chain of Thought**

<a href="#chain-of-thought">
<img src="https://img.shields.io/badge/Step_by_Step-Reasoning-4ECDC4?style=for-the-badge" alt="Chain of Thought"/>
</a>

*Break down complex tasks*

</td>
<td align="center" width="25%">

**🎓 Learning Styles**

<a href="#few-shot-learning">
<img src="https://img.shields.io/badge/Show_Examples-Teach-45B7D1?style=for-the-badge" alt="Few-Shot"/>
</a>

*Teach AI with examples*

</td>
<td align="center" width="25%">

**🌡️ Creativity Control**

<a href="#temperature-and-creativity">
<img src="https://img.shields.io/badge/Control_Output-Tune-9B59B6?style=for-the-badge" alt="Temperature"/>
</a>

*Adjust AI creativity*

</td>
</tr>
</table>

<details>
<summary><strong>📋 Complete Concept Overview</strong> <em>(Click to see all 7 concepts)</em></summary>

<br/>

| **Concept** | **What It Does** | **When to Use** | **Impact Level** |
|-------------|------------------|-----------------|------------------|
| 📝 **Context & Specificity** | Makes prompts clear and targeted | Always - foundation of good prompts | ⭐⭐⭐⭐⭐ |
| 🔗 **Chain of Thought** | Breaks complex problems into steps | Problem-solving, analysis | ⭐⭐⭐⭐⭐ |
| 🎓 **Few-Shot Learning** | Teaches AI with examples | Style matching, consistency | ⭐⭐⭐⭐ |
| 🆚 **Zero vs Few-Shot** | Choosing the right approach | Task complexity decisions | ⭐⭐⭐ |
| ⛓️ **Prompt Chaining** | Connects multiple prompts | Large, complex projects | ⭐⭐⭐⭐ |
| 🌡️ **Temperature Control** | Adjusts creativity vs consistency | Creative vs factual tasks | ⭐⭐⭐ |
| 🪙 **Token Management** | Optimizes prompt efficiency | Long conversations, costs | ⭐⭐⭐ |

</details>

---

## 🎨 Context and Specificity

### What It Is
The more specific and contextual information you provide, the better AI can tailor its response to your needs.

### Simple Analogy
Think of giving directions to someone:
- **Vague**: "Go to the store"
- **Specific**: "Go to the Whole Foods on Main Street, buy organic bananas from the produce section"

### Examples

#### ❌ Vague Prompt
```
"Write content about dogs."
```

#### ✅ Specific Prompt
```
"Write a 300-word blog post about golden retriever care tips for new dog owners, 
focusing on feeding, exercise, and grooming. Use a friendly, encouraging tone."
```

### Key Elements of Good Context:
- **Who** is your audience?
- **What** exactly do you need?
- **Why** are you creating this?
- **When** will this be used?
- **Where** will this appear?
- **How** should it sound/look?

---

## 🔗 Chain of Thought

### What It Is
Breaking down complex problems into step-by-step thinking, just like you would explain your reasoning to a friend.

### Simple Analogy
Instead of asking someone to "solve this math problem," you ask them to "show their work" - explaining each step.

### Examples

#### Without Chain of Thought
```
"What's the best marketing strategy for a new coffee shop?"
```

#### With Chain of Thought
```
"Help me develop a marketing strategy for a new coffee shop. Let's think through this step by step:

1. First, analyze the target customer base
2. Then, identify the unique value proposition
3. Next, consider budget constraints
4. Finally, recommend specific tactics

Please walk through each step with reasoning."
```

### When to Use Chain of Thought:
- Complex problem-solving
- Mathematical calculations
- Multi-step processes
- Decision-making scenarios
- Analysis and reasoning tasks

---

## 🎓 Few-Shot Learning

### What It Is
Teaching AI through examples - showing it a few instances of what you want before asking for new output.

### Simple Analogy
Like showing someone a few examples of good resume formats before asking them to write one.

### Example: Email Tone

```
Here are examples of the professional but friendly tone I want:

Example 1:
"Hi Sarah, Thanks for reaching out! I'd be happy to discuss this project. When works best for you this week?"

Example 2:  
"Hello Tom, Great question! Let me walk you through the process step by step."

Now write a similar response to this email: [insert email]
```

### Benefits:
- More consistent output
- Better understanding of style/format
- Reduced need for multiple revisions
- Clearer expectations

---

## 🆚 Zero-Shot vs Few-Shot

### Zero-Shot
Ask AI to do something without examples
```
"Write a product description for running shoes."
```

### Few-Shot  
Provide examples first
```
"Here are two product descriptions I like:
[Example 1]
[Example 2]

Now write one for these running shoes: [product details]"
```

### When to Use Each:

| **Use Zero-Shot When:** | **Use Few-Shot When:** |
|------------------------|----------------------|
| Task is straightforward | You have specific style preferences |
| You want creative freedom | Consistency is important |
| Examples aren't available | You've found good examples |
| General knowledge task | Specialized format needed |

---

## 🔄 Prompt Chaining

### What It Is
Breaking large tasks into smaller, connected prompts that build on each other.

### Simple Analogy
Like cooking a complex meal - you don't do everything at once. You prep ingredients first, then cook each component, then combine them.

### Example: Blog Post Creation

**Prompt 1**: Planning
```
"Help me brainstorm 10 blog post ideas about sustainable living for beginners."
```

**Prompt 2**: Outlining  
```
"Create a detailed outline for a blog post titled 'Zero Waste Kitchen: 5 Simple Swaps for Beginners'"
```

**Prompt 3**: Writing
```
"Using this outline, write the introduction section focusing on encouraging beginners and addressing common concerns."
```

### Benefits:
- Better quality output
- Easier to review and revise
- More control over the process
- Less overwhelming for complex projects

---

## 🌡️ Temperature and Creativity

### What It Is
A setting that controls how creative or predictable AI responses are.

### Simple Analogy
Think of it like a creativity dial:
- **Low temperature (0.1-0.3)**: Conservative, predictable, consistent
- **High temperature (0.7-1.0)**: Creative, varied, sometimes unexpected

### Examples

#### Low Temperature Use Cases:
- Technical documentation
- Factual content
- Formal business writing
- Data analysis
- Code generation

#### High Temperature Use Cases:
- Creative writing
- Brainstorming
- Marketing copy
- Storytelling
- Art descriptions

### How to Request Different "Temperatures":
```
"Write a creative, imaginative story..." (implies higher creativity)
"Write a precise, factual summary..." (implies lower creativity)
```

---

## 📏 Token Limits and Context Windows

### What It Is
AI models have limits on how much text they can process and remember in a single conversation.

### Simple Analogy
Think of it like short-term memory - there's only so much information someone can keep in mind at once.

### Practical Implications:

#### For Long Documents:
```
"I have a 50-page report to analyze. Let me share it in sections. 
Here's section 1: [content]
Please analyze this section, then I'll share section 2."
```

#### For Complex Projects:
```
"This is part 1 of a 3-part project. After each part, I'll ask you to 
summarize what we've covered before moving to the next part."
```

### Best Practices:
- Break long tasks into chunks
- Summarize important points as you go
- Reference key information in each new prompt
- Start fresh conversations for unrelated topics

---

## 🚀 Putting It All Together

### The CLEAR Framework

**C**ontext: What's the situation?
**L**ength: How long should the response be?
**E**xamples: Can you show what you want?
**A**udience: Who is this for?
**R**ole: What perspective should AI take?

### Example Using CLEAR:
```
Context: I'm launching a new productivity app for remote workers
Length: Write a 150-word elevator pitch  
Examples: Like how Slack describes itself as "where work flows"
Audience: For potential investors at a startup demo day
Role: Act as a confident startup founder
```

---

## 📚 What's Next?

- **Ready to practice?** Check out [examples](../examples/) for hands-on prompts
- **Want role-specific help?** Explore [use-cases](../use-cases/) for your profession
- **Need advanced techniques?** Dive into [advanced techniques](../techniques/advanced/)
- **Want to understand the tech?** See [architecture](../architecture/) for how AI works

Remember: These concepts work best when combined. Don't feel like you need to use all of them in every prompt - choose what fits your specific needs!