<div align="center">

# 🔧 Prompt Engineering for Developers

<p align="center">
  <img src="https://img.shields.io/badge/Target_Audience-Developers-blue?style=for-the-badge&logo=github" alt="For Developers"/>
  <img src="https://img.shields.io/badge/Skill_Level-All_Levels-green?style=for-the-badge" alt="All Levels"/>
  <img src="https://img.shields.io/badge/Focus-Code_Quality-orange?style=for-the-badge&logo=codereview" alt="Code Quality"/>
</p>

<p align="center">
  <strong>Supercharge your development workflow with AI</strong><br/>
  From code generation to debugging, documentation to architecture decisions
</p>

</div>

---

## 🚀 Quick Jump Navigation

<div align="center">

### Choose Your Development Task

</div>

<table>
<tr>
<td align="center" width="25%">

**💻 Code Generation**

<a href="#code-generation">
<img src="https://img.shields.io/badge/Generate_Code-Start-FF6B6B?style=for-the-badge" alt="Code Generation"/>
</a>

*Write functions, APIs, components*

</td>
<td align="center" width="25%">

**🐛 Debug & Fix**

<a href="#debugging--troubleshooting">
<img src="https://img.shields.io/badge/Debug_Issues-Fix-4ECDC4?style=for-the-badge" alt="Debug"/>
</a>

*Solve errors and optimize*

</td>
<td align="center" width="25%">

**📚 Documentation**

<a href="#documentation">
<img src="https://img.shields.io/badge/Write_Docs-Document-45B7D1?style=for-the-badge" alt="Documentation"/>
</a>

*APIs, functions, guides*

</td>
<td align="center" width="25%">

**🧪 Testing**

<a href="#testing">
<img src="https://img.shields.io/badge/Create_Tests-Test-9B59B6?style=for-the-badge" alt="Testing"/>
</a>

*Unit, integration, E2E*

</td>
</tr>
</table>

<details>
<summary><strong>📋 Complete Development Toolkit</strong> <em>(Click to see all features)</em></summary>

<br/>

| **Development Area** | **What You'll Learn** | **Time Saved** |
|---------------------|----------------------|----------------|
| 💻 **Code Generation** | Functions, APIs, components, algorithms | 60-80% |
| 🐛 **Debugging** | Error analysis, performance fixes | 40-60% |
| 🔍 **Code Review** | Best practices, security, optimization | 50-70% |
| 📚 **Documentation** | API docs, README files, comments | 70-90% |
| 🧪 **Testing** | Unit tests, integration tests | 50-80% |
| 🏗️ **Architecture** | Design patterns, system design | 30-50% |
| 📖 **Learning** | New frameworks, languages | 40-60% |

</details>

---

## 💻 Code Generation

### Basic Code Generation Template
```
Generate [language] code that [functionality] with these requirements:
- [Requirement 1]
- [Requirement 2] 
- [Requirement 3]

Include comments explaining the logic and handle edge cases.
```

### Specific Examples

#### API Endpoint Creation
```
Create a REST API endpoint in Node.js/Express that:
- Accepts user registration data (email, password, name)
- Validates email format and password strength
- Checks for existing users
- Hashes passwords using bcrypt
- Returns appropriate HTTP status codes
- Includes error handling for database failures

Include TypeScript types and comprehensive comments.
```

#### Database Query Generation
```
Write a SQL query that:
- Joins users, orders, and products tables
- Finds all users who purchased more than $500 worth of products in the last 30 days
- Groups results by user
- Orders by total purchase amount descending
- Include user name, email, total spent, and number of orders

Also provide the equivalent using Prisma ORM.
```

#### React Component Creation
```
Create a React TypeScript component for a product card that:
- Accepts props: product (with name, price, image, description)
- Shows product image with lazy loading
- Displays price with currency formatting
- Has an "Add to Cart" button with loading state
- Uses CSS modules for styling
- Includes accessibility attributes
- Handles image loading errors with fallback
```

---

## 🐛 Debugging & Troubleshooting

### Debugging Prompt Template
```
I'm getting this error in [language/framework]:
[Paste error message]

Here's the relevant code:
[Paste code]

Context:
- What I'm trying to achieve: [goal]
- When it happens: [circumstances]
- What I've tried: [attempted solutions]

Please help me understand what's wrong and provide a fix.
```

### Specific Examples

#### JavaScript Error Analysis
```
I'm getting "Cannot read property 'map' of undefined" in my React component:

```javascript
const UserList = ({ users }) => {
  return (
    <div>
      {users.map(user => <div key={user.id}>{user.name}</div>)}
    </div>
  );
};
```

Context:
- This happens when the component first renders
- Users data comes from an API call
- The API call is async and takes time to complete

Please explain why this happens and show me 3 different ways to fix it.
```

#### Performance Issue Diagnosis
```
My Python script is running very slowly on large datasets:

```python
def process_data(data_list):
    result = []
    for item in data_list:
        if item['status'] == 'active':
            processed = expensive_operation(item)
            result.append(processed)
    return result
```

Context:
- data_list has 100,000+ items
- expensive_operation takes ~10ms per item
- Current execution time is 20+ minutes
- Memory usage keeps increasing

Analyze the performance bottlenecks and suggest optimizations.
```

---

## 🔍 Code Review & Optimization

### Code Review Template
```
Please review this [language] code for:
- Best practices and conventions
- Security vulnerabilities
- Performance improvements
- Readability and maintainability
- Error handling
- Edge cases

[Paste code]

Context: [brief description of what the code does]
```

### Optimization Examples

#### Algorithm Optimization
```
Review and optimize this sorting algorithm:

```python
def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n-i-1):
            if arr[j] > arr[j+1]:
                arr[j], arr[j+1] = arr[j+1], arr[j]
    return arr
```

Please suggest:
1. Time/space complexity improvements
2. More efficient algorithms for this use case
3. Python-specific optimizations
4. When to use built-in sort vs custom implementation
```

#### Database Query Optimization
```
This query is slow on large tables. Please optimize:

```sql
SELECT u.name, u.email, COUNT(o.id) as order_count
FROM users u
LEFT JOIN orders o ON u.id = o.user_id
WHERE u.created_at >= '2024-01-01'
GROUP BY u.id, u.name, u.email
HAVING COUNT(o.id) > 5
ORDER BY order_count DESC;
```

Table info:
- users: 1M+ records, indexed on id and created_at
- orders: 5M+ records, indexed on id and user_id
- Query currently takes 30+ seconds

Suggest indexing strategies and query improvements.
```

---

## 📚 Documentation

### Documentation Templates

#### API Documentation
```
Generate comprehensive API documentation for this endpoint:

```javascript
app.post('/api/users', async (req, res) => {
  // [paste your endpoint code]
});
```

Include:
- Endpoint description and purpose
- Request/response formats with examples
- HTTP status codes
- Error scenarios
- Authentication requirements
- Rate limiting info
- OpenAPI/Swagger format
```

#### Function Documentation
```
Create detailed JSDoc comments for this function:

```javascript
function calculateShippingCost(weight, distance, priority) {
  // [function implementation]
}
```

Include parameter types, return values, examples, and edge cases.
```

#### README Generation
```
Generate a comprehensive README.md for a project with these characteristics:
- [Language/framework]
- [Brief project description]
- [Key features]
- [Dependencies]

Include:
- Installation instructions
- Usage examples
- Configuration options
- Contributing guidelines
- License information
- Troubleshooting section
```

---

## 🧪 Testing

### Test Generation Templates

#### Unit Test Creation
```
Generate comprehensive unit tests for this [language] function:

[Paste function code]

Include tests for:
- Happy path scenarios
- Edge cases
- Error conditions
- Boundary values
- Mock dependencies where needed

Use [testing framework] and follow [language] testing best practices.
```

#### Integration Test Creation
```
Create integration tests for this API endpoint:

[Paste endpoint code]

Test scenarios:
- Valid request with expected response
- Invalid input data
- Authentication failures
- Database connection issues
- Rate limiting
- Concurrent requests

Use [testing framework] and include setup/teardown code.
```

### Specific Examples

#### React Component Testing
```
Generate Jest/React Testing Library tests for this component:

```jsx
const LoginForm = ({ onSubmit, loading }) => {
  const [email, setEmail] = useState('');
  const [password, setPassword] = useState('');
  
  const handleSubmit = (e) => {
    e.preventDefault();
    onSubmit({ email, password });
  };

  return (
    <form onSubmit={handleSubmit}>
      <input 
        type="email" 
        value={email} 
        onChange={(e) => setEmail(e.target.value)}
        data-testid="email-input"
      />
      <input 
        type="password" 
        value={password} 
        onChange={(e) => setPassword(e.target.value)}
        data-testid="password-input"
      />
      <button type="submit" disabled={loading}>
        {loading ? 'Logging in...' : 'Login'}
      </button>
    </form>
  );
};
```

Include tests for form submission, input changes, loading states, and validation.
```

---

## 🏗️ Architecture & Design

### Architecture Decision Templates

#### System Design Review
```
I'm designing a [type of system] with these requirements:
- [Requirement 1]
- [Requirement 2]
- [Requirement 3]

Current proposed architecture:
[Describe your current design]

Please review and suggest:
1. Potential scalability issues
2. Security considerations
3. Alternative approaches
4. Trade-offs and pros/cons
5. Technology stack recommendations
```

#### Database Schema Design
```
Help me design a database schema for [application type] with these entities:
- [Entity 1 with attributes]
- [Entity 2 with attributes]
- [Relationships]

Requirements:
- [Performance requirements]
- [Scalability needs]
- [Query patterns]

Suggest:
1. Table structure with relationships
2. Indexing strategy
3. Normalization level
4. Potential bottlenecks
```

---

## 📖 Learning New Technologies

### Learning Templates

#### Technology Comparison
```
I need to choose between [Technology A] and [Technology B] for [specific use case].

Project requirements:
- [Requirement 1]
- [Requirement 2]
- Team context: [team size, experience level]
- Timeline: [project timeline]

Please compare them on:
1. Learning curve
2. Performance characteristics
3. Community support
4. Long-term maintenance
5. Ecosystem and tooling
6. Specific recommendation with reasoning
```

#### Quick Start Guide Request
```
Create a quick start guide for [technology] covering:
1. Installation and setup
2. Basic "Hello World" example
3. Key concepts I need to understand
4. Common gotchas for beginners
5. Best learning resources
6. Next steps after basics

My background: [your experience level and relevant technologies]
```

---

## 🎯 Advanced Developer Prompts

### Code Refactoring
```
Refactor this [language] code to improve:
- Readability and maintainability
- Performance
- Testability
- Following SOLID principles
- Design patterns where appropriate

[Paste code]

Explain the changes and why they improve the code.
```

### Architecture Pattern Implementation
```
Show me how to implement the [Pattern Name] pattern in [language] for this scenario:
[Describe the problem]

Include:
- Pattern explanation
- Implementation code
- Usage examples
- When to use vs alternatives
- Common mistakes to avoid
```

---

## 📋 Ready-to-Use Templates

### Quick Development Tasks

#### Bug Report Analysis
```
Analyze this bug report and suggest debugging steps:

Bug Description: [paste bug description]
Steps to Reproduce: [paste steps]
Expected vs Actual Behavior: [paste behaviors]
Environment: [system info]

Suggest:
1. Most likely causes
2. Debugging steps to isolate the issue
3. Potential fixes
4. Prevention strategies
```

#### Code Migration
```
Help me migrate this code from [Old Technology] to [New Technology]:

[Paste original code]

Requirements:
- Maintain same functionality
- Follow [New Technology] best practices
- Optimize for [specific goals]
- Explain major differences and improvements
```

---

## 🚀 Pro Tips for Developers

### 1. **Iterative Refinement**
Start with a basic prompt, then refine based on output:
```
Initial: "Create a login function"
Refined: "Create a secure login function with password hashing, rate limiting, and JWT tokens"
```

### 2. **Context is King**
Always provide:
- Language/framework version
- Project constraints
- Team preferences
- Performance requirements

### 3. **Ask for Explanations**
```
"Explain your code choices and suggest alternatives"
```

### 4. **Request Best Practices**
```
"Include error handling, logging, and follow [language] conventions"
```

### 5. **Get Multiple Solutions**
```
"Show me 3 different approaches with pros/cons for each"
```

---

Ready to level up your development workflow? Check out the [advanced techniques](../../techniques/advanced/) or browse more [examples](../../examples/) for inspiration!