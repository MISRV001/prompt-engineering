<div align="center">

# 🧪 Prompt Engineering for QA Engineers

<p align="center">
  <img src="https://img.shields.io/badge/Target_Audience-QA_Engineers-green?style=for-the-badge&logo=checkmarx" alt="QA Engineers"/>
  <img src="https://img.shields.io/badge/Testing_Types-All_Covered-blue?style=for-the-badge" alt="All Testing Types"/>
  <img src="https://img.shields.io/badge/Quality_Focus-High-orange?style=for-the-badge&logo=quality" alt="High Quality"/>
</p>

<p align="center">
  <strong>Revolutionize your testing workflow with AI assistance</strong><br/>
  From test case generation to automation, bug analysis to quality reporting
</p>

</div>

---

## 🔍 QA Toolkit Navigation

<div align="center">

### Choose Your Testing Focus

</div>

<table>
<tr>
<td align="center" width="25%">

**📝 Test Cases**

<a href="#test-case-generation">
<img src="https://img.shields.io/badge/Generate_Tests-Create-FF6B6B?style=for-the-badge" alt="Test Cases"/>
</a>

*Comprehensive test scenarios*

</td>
<td align="center" width="25%">

**🐛 Bug Analysis**

<a href="#bug-analysis--reporting">
<img src="https://img.shields.io/badge/Analyze_Bugs-Debug-4ECDC4?style=for-the-badge" alt="Bug Analysis"/>
</a>

*Root cause analysis*

</td>
<td align="center" width="25%">

**🤖 Automation**

<a href="#test-automation">
<img src="https://img.shields.io/badge/Automate_Tests-Scale-45B7D1?style=for-the-badge" alt="Automation"/>
</a>

*Scripts and frameworks*

</td>
<td align="center" width="25%">

**📊 Reporting**

<a href="#documentation--reporting">
<img src="https://img.shields.io/badge/Create_Reports-Document-9B59B6?style=for-the-badge" alt="Reporting"/>
</a>

*Quality documentation*

</td>
</tr>
</table>

<details>
<summary><strong>🎯 Complete QA Arsenal</strong> <em>(Click to see all testing areas)</em></summary>

<br/>

| **Testing Area** | **AI Assistance** | **Time Savings** | **Quality Impact** |
|------------------|-------------------|------------------|-------------------|
| 📝 **Test Case Generation** | Comprehensive scenarios, edge cases | 70-80% | ⭐⭐⭐⭐⭐ |
| 🐛 **Bug Analysis** | Root cause identification, debugging | 50-60% | ⭐⭐⭐⭐⭐ |
| 🤖 **Test Automation** | Script generation, framework setup | 60-70% | ⭐⭐⭐⭐ |
| 🌐 **API Testing** | Request/response validation | 65-75% | ⭐⭐⭐⭐ |
| ⚡ **Performance Testing** | Load scenarios, bottleneck analysis | 55-65% | ⭐⭐⭐⭐ |
| 🔒 **Security Testing** | Vulnerability assessment | 40-50% | ⭐⭐⭐⭐⭐ |
| 📊 **Test Data** | Data generation, management | 80-90% | ⭐⭐⭐ |
| 📋 **Documentation** | Reports, test plans | 75-85% | ⭐⭐⭐⭐ |

</details>

---

## 📝 Test Case Generation

### Comprehensive Test Case Template
```
Generate comprehensive test cases for [feature/functionality] with these details:

Feature Description: [detailed description]
Acceptance Criteria: 
- [Criteria 1]
- [Criteria 2]

Include test cases for:
- Happy path scenarios
- Edge cases
- Negative testing
- Boundary value testing
- Error handling

Format: [specify format - Gherkin, traditional, etc.]
```

### Specific Examples

#### User Registration Testing
```
Generate test cases for user registration functionality:

Requirements:
- Email must be unique and valid format
- Password must be 8-20 characters with special characters
- Username must be 3-30 characters, alphanumeric only
- Terms of service agreement required
- Email verification sent after registration

Include:
1. Positive test scenarios
2. Input validation tests
3. Security test cases
4. UI/UX test scenarios
5. Integration test cases

Format as Gherkin scenarios with Given/When/Then structure.
```

#### E-commerce Checkout Testing
```
Create test cases for checkout process covering:

Features:
- Cart management (add/remove/modify items)
- Multiple payment methods (credit card, PayPal, digital wallet)
- Shipping options and calculations
- Discount codes and promotions
- Guest vs registered user checkout

Include test cases for:
- Complete purchase flows
- Payment failures
- Inventory issues
- Network interruptions
- Cross-browser compatibility
- Mobile responsiveness

Prioritize by risk level (High/Medium/Low).
```

---

## 🐛 Bug Analysis & Reporting

### Bug Analysis Template
```
Analyze this bug and provide detailed investigation guidance:

Bug Description: [description]
Steps to Reproduce: [steps]
Expected vs Actual Behavior: [comparison]
Environment: [browser, OS, version, etc.]

Please provide:
1. Root cause analysis
2. Severity and priority assessment
3. Additional test scenarios to verify the fix
4. Regression testing recommendations
5. Similar areas that might be affected
```

### Specific Examples

#### Performance Bug Investigation
```
Investigate this performance issue:

Problem: Page load time increased from 2s to 8s after recent deployment
Affected Pages: Product listing and search results
Environment: Production, all browsers
User Reports: 60% increase in bounce rate

Analyze and suggest:
1. Potential causes (code, database, infrastructure)
2. Debugging steps and tools to use
3. Performance metrics to monitor
4. Test scenarios to validate fixes
5. Prevention strategies for future releases
```

#### Cross-Browser Compatibility Issue
```
Analyze this cross-browser bug:

Issue: Form submission fails on Safari but works on Chrome/Firefox
Form: Contact form with file upload
Error: No visible error message, form appears to submit but data not saved
Safari Version: 16.x on macOS

Provide:
1. Likely technical causes
2. Browser-specific testing strategy  
3. Debugging steps for Safari
4. Compatibility testing checklist
5. Workaround suggestions while fix is developed
```

---

## 🤖 Modern Test Automation with Playwright

### Comprehensive Automation Strategy Framework
```
Design a modern test automation strategy for [application type]:

Application Architecture:
- Frontend: [NextJS/React/Vue] with [TypeScript/JavaScript]
- Backend: [Node.js/Java/.NET] with [REST/GraphQL] APIs
- Database: [PostgreSQL/MongoDB/Redis]
- Infrastructure: [AWS/Azure/GCP] with [Docker/Kubernetes]
- CI/CD: [GitHub Actions/Jenkins/GitLab CI]

Current State:
- Manual testing effort: [hours per release]
- Test coverage: [current percentage]
- Release frequency: [daily/weekly/monthly]
- Team composition: [developers/QA/DevOps ratios]
- Pain points: [specific issues and bottlenecks]

Target Strategy:
1. Test pyramid optimization (70% unit, 20% integration, 10% E2E)
2. Shift-left testing implementation
3. Parallel execution and CI/CD integration
4. Cross-browser and mobile testing
5. Visual regression testing
6. Performance testing integration
7. API contract testing
8. Security testing automation

Provide:
- Framework selection rationale (Playwright vs Cypress vs Selenium)
- Implementation roadmap with phases and timelines
- ROI calculations and success metrics
- Team training and skill development plan
- Maintenance and scaling strategies
- Tool integration recommendations
```

### 🎭 Playwright Automation Examples

#### Modern E2E Testing Framework Setup
```
Create a comprehensive Playwright testing framework for a NextJS e-commerce application:

Application Features:
- User authentication (login/register/OAuth)
- Product catalog with search and filtering
- Shopping cart and checkout process
- Payment integration (Stripe)
- User dashboard and order history
- Admin panel for product management
- Real-time notifications via WebSockets

Framework Requirements:
- TypeScript for type safety
- Page Object Model architecture
- Custom fixtures for test data
- Cross-browser testing (Chrome, Firefox, Safari, Edge)
- Mobile and desktop viewports
- Visual regression testing
- API mocking and stubbing
- Database state management
- CI/CD integration with GitHub Actions
- Parallel execution capabilities
- Detailed reporting with screenshots/videos
- Flaky test detection and retry mechanisms

Include:
1. Project structure and configuration
2. Base page classes and utilities
3. Test data factories and fixtures
4. Custom assertions and helpers
5. CI/CD pipeline configuration
6. Reporting and notifications setup
```

#### Advanced Playwright Test Scenarios
```
Generate Playwright test automation for complex user workflows:

Scenario 1: Complete E-commerce Purchase Journey
- User registration with email verification
- Browse products with dynamic loading
- Apply filters and sort options
- Add multiple items to cart from different categories
- Apply discount codes and validate pricing
- Guest checkout vs logged-in user checkout
- Multiple payment methods testing
- Order confirmation and email verification
- Track order status updates

Scenario 2: Admin Panel Management
- Admin login with MFA
- Product management (CRUD operations)
- Bulk upload with CSV validation
- Inventory management with real-time updates
- User management and role assignments
- Analytics dashboard interactions
- Report generation and downloads
- System settings configuration

Technical Requirements:
- Handle dynamic content loading (API responses)
- Wait for network requests completion
- Manage browser state and cookies
- Handle file uploads and downloads
- Interact with iframes and pop-ups
- Test responsive design breakpoints
- Validate form validation messages
- Test accessibility compliance (WCAG)
- Performance metrics collection
- Error handling and recovery scenarios

For each scenario, include:
1. Test data setup and teardown
2. Page object implementations
3. Custom fixtures and utilities
4. Assertion strategies
5. Error handling patterns
6. Performance measurement points
```

#### Playwright Visual & Accessibility Testing
```
Implement comprehensive visual and accessibility testing:

Visual Regression Testing:
- Full page screenshots across viewports
- Component-level visual testing
- Cross-browser visual comparison
- Mobile vs desktop layout validation
- Dark mode vs light mode comparison
- Dynamic content visual testing
- Animation and transition testing
- Print stylesheet validation

```typescript
// Example visual testing implementation
test.describe('Visual Regression Suite', () => {
  test('Homepage visual comparison', async ({ page }) => {
    await page.goto('/');
    await page.waitForLoadState('networkidle');
    
    // Full page screenshot
    await expect(page).toHaveScreenshot('homepage-full.png', {
      fullPage: true,
      animations: 'disabled'
    });
    
    // Component-level screenshots
    await expect(page.locator('[data-testid="header"]')).toHaveScreenshot('header-component.png');
    await expect(page.locator('[data-testid="hero-section"]')).toHaveScreenshot('hero-section.png');
  });
});
```

Accessibility Testing Integration:
- WCAG 2.1 AA compliance verification
- Keyboard navigation testing
- Screen reader compatibility
- Color contrast validation
- Focus management testing
- ARIA attributes verification
- Alternative text validation
- Form accessibility testing

Include:
1. axe-core integration with Playwright
2. Custom accessibility assertions
3. Automated accessibility reporting
4. Manual accessibility test scenarios
5. Accessibility test data and fixtures
```

#### Playwright API Testing Integration
```
Create comprehensive API testing within Playwright framework:

API Testing Strategy:
- REST API endpoint validation
- GraphQL query and mutation testing
- Authentication and authorization testing
- Rate limiting and error handling verification
- Data validation and schema compliance
- Performance and load testing integration
- Mock server setup for testing
- Contract testing with consumer-driven contracts

```typescript
// Example API testing implementation
test.describe('API Integration Tests', () => {
  test('User authentication flow', async ({ request }) => {
    // Login API test
    const loginResponse = await request.post('/api/auth/login', {
      data: {
        email: 'test@example.com',
        password: 'secure123'
      }
    });
    
    expect(loginResponse.status()).toBe(200);
    const loginData = await loginResponse.json();
    expect(loginData).toHaveProperty('token');
    expect(loginData).toHaveProperty('user');
    
    // Use token for authenticated requests
    const userProfile = await request.get('/api/user/profile', {
      headers: {
        'Authorization': `Bearer ${loginData.token}`
      }
    });
    
    expect(userProfile.status()).toBe(200);
    const profile = await userProfile.json();
    expect(profile.email).toBe('test@example.com');
  });
});
```

API Test Categories:
1. Authentication and session management
2. CRUD operations with data validation
3. Error handling and edge cases
4. Rate limiting and throttling
5. File upload and download
6. Real-time features (WebSockets)
7. Third-party API integrations
8. Database consistency validation
9. Caching behavior verification
10. Security vulnerability testing

Framework Integration:
- Shared test data between UI and API tests
- API response mocking for UI tests
- Database state synchronization
- Test environment management
- Continuous integration pipeline
- Performance metrics collection
```

---

## 🌐 Advanced API Testing with Schema Validation

### Comprehensive API Testing Framework
```
Create a comprehensive API testing strategy for [application]:

API Architecture:
- REST APIs with OpenAPI 3.0 specification
- GraphQL APIs with schema definition
- WebSocket real-time communication
- Authentication: JWT with refresh tokens
- Authorization: Role-based access control (RBAC)
- Rate limiting: [requests per minute/hour]
- Pagination: Cursor-based and offset-based
- File upload/download capabilities
- Webhooks for external integrations

Testing Requirements:
1. Contract testing with schema validation
2. Performance testing with load scenarios
3. Security testing (OWASP API Top 10)
4. Data integrity and consistency testing
5. Error handling and recovery testing
6. Integration testing with external services
7. Compatibility testing across API versions
8. Monitoring and observability testing

Tools Integration:
- Jest/Mocha for test framework
- JSON Schema validation
- OpenAPI schema validation
- Postman/Newman for collection running
- K6 for performance testing
- OWASP ZAP for security testing
- Wiremock for API mocking
- CI/CD pipeline integration

Provide:
- Test strategy and approach
- Test data management strategy
- Environment setup and configuration
- Reporting and metrics collection
- Automation framework architecture
```

### 🔧 Schema-Driven API Testing

#### OpenAPI Schema Validation Testing
```
Generate comprehensive API tests with OpenAPI schema validation:

API Specification:
```yaml
# users-api.yaml
openapi: 3.0.3
info:
  title: User Management API
  version: 2.0.0
paths:
  /api/v2/users:
    post:
      summary: Create new user
      requestBody:
        content:
          application/json:
            schema:
              $ref: '#/components/schemas/CreateUserRequest'
      responses:
        '201':
          content:
            application/json:
              schema:
                $ref: '#/components/schemas/UserResponse'
        '400':
          content:
            application/json:
              schema:
                $ref: '#/components/schemas/ErrorResponse'
components:
  schemas:
    CreateUserRequest:
      type: object
      required: [email, password, firstName, lastName]
      properties:
        email:
          type: string
          format: email
          maxLength: 255
        password:
          type: string
          minLength: 8
          pattern: '^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)(?=.*[@$!%*?&])[A-Za-z\d@$!%*?&]'
        firstName:
          type: string
          minLength: 1
          maxLength: 50
        lastName:
          type: string
          minLength: 1
          maxLength: 50
        dateOfBirth:
          type: string
          format: date
        phoneNumber:
          type: string
          pattern: '^\+[1-9]\d{1,14}$'
```

Test Implementation Requirements:
1. Schema validation for request/response bodies
2. Data type validation (string, number, boolean, array, object)
3. Format validation (email, date, uuid, uri)
4. Range validation (minLength, maxLength, minimum, maximum)
5. Pattern validation (regex patterns)
6. Required field validation
7. Additional properties handling
8. Enum value validation
9. Nested object and array validation
10. Custom validation rules

Include:
- Positive test cases with valid data
- Negative test cases with invalid data
- Boundary value testing
- Schema evolution testing
- Contract testing implementation
```

#### GraphQL API Testing with Schema Validation
```
Create comprehensive GraphQL API testing with schema validation:

GraphQL Schema:
```graphql
type User {
  id: ID!
  email: String!
  firstName: String!
  lastName: String!
  dateOfBirth: Date
  createdAt: DateTime!
  updatedAt: DateTime!
  posts: [Post!]!
  profile: UserProfile
}

type Post {
  id: ID!
  title: String!
  content: String!
  publishedAt: DateTime
  author: User!
  tags: [String!]!
  viewCount: Int!
}

input CreateUserInput {
  email: String!
  password: String!
  firstName: String!
  lastName: String!
  dateOfBirth: Date
}

type Query {
  users(first: Int, after: String, filter: UserFilter): UserConnection!
  user(id: ID!): User
  posts(first: Int, after: String): PostConnection!
}

type Mutation {
  createUser(input: CreateUserInput!): User!
  updateUser(id: ID!, input: UpdateUserInput!): User!
  deleteUser(id: ID!): Boolean!
}

type Subscription {
  userCreated: User!
  postPublished: Post!
}
```

Testing Scenarios:
1. Query testing with field selection validation
2. Mutation testing with input validation
3. Subscription testing for real-time updates
4. Schema introspection testing
5. Query complexity and depth analysis
6. Performance testing with nested queries
7. Authentication and authorization testing
8. Error handling and validation
9. Pagination testing (cursor-based)
10. File upload testing (multipart/form-data)

Test Implementation:
- GraphQL schema validation
- Query syntax validation
- Response data structure validation
- Custom scalar type validation
- Directive validation
- Fragment validation
- Variable validation
- Subscription lifecycle testing

Include:
- Query and mutation test cases
- Schema validation utilities
- Mock data generation
- Performance benchmarking
- Error scenario testing
```

#### JSON Schema Validation Framework
```
Implement robust JSON Schema validation for API testing:

Schema Definition Strategy:
```json
{
  "$schema": "https://json-schema.org/draft/2020-12/schema",
  "$id": "https://api.example.com/schemas/user.json",
  "title": "User",
  "type": "object",
  "properties": {
    "id": {
      "type": "string",
      "format": "uuid"
    },
    "email": {
      "type": "string",
      "format": "email",
      "maxLength": 255
    },
    "profile": {
      "$ref": "#/$defs/UserProfile"
    },
    "preferences": {
      "type": "object",
      "properties": {
        "notifications": {
          "type": "object",
          "properties": {
            "email": { "type": "boolean" },
            "sms": { "type": "boolean" },
            "push": { "type": "boolean" }
          },
          "additionalProperties": false
        },
        "privacy": {
          "type": "string",
          "enum": ["public", "friends", "private"]
        }
      }
    }
  },
  "required": ["id", "email"],
  "additionalProperties": false,
  "$defs": {
    "UserProfile": {
      "type": "object",
      "properties": {
        "firstName": { "type": "string", "minLength": 1 },
        "lastName": { "type": "string", "minLength": 1 },
        "bio": { "type": "string", "maxLength": 500 },
        "avatar": { "type": "string", "format": "uri" }
      }
    }
  }
}
```

Validation Testing Framework:
1. Schema compilation and validation
2. Response data validation against schema
3. Custom format validation (email, uuid, uri, date)
4. Conditional schema validation (if/then/else)
5. Cross-field validation rules
6. Dynamic schema validation
7. Schema versioning and backward compatibility
8. Custom keyword validation
9. Error message validation and clarity
10. Performance impact of validation

Implementation Components:
- Schema registry management
- Validation middleware integration
- Custom assertion helpers
- Error reporting and logging
- Schema documentation generation
- Test data generation from schemas
- Schema-driven mock server
- Regression testing for schema changes

Tools Integration:
- Ajv for JSON Schema validation
- JSON Schema Faker for test data generation
- JSON Schema to OpenAPI conversion
- Schema diff tools for version comparison
- Integration with testing frameworks
```

### 🔐 Advanced API Security Testing

#### OWASP API Security Testing
```
Implement comprehensive API security testing based on OWASP API Security Top 10:

Security Test Categories:

1. Broken Object Level Authorization (BOLA)
   - Test accessing other users' resources
   - Verify object-level permission checks
   - Test horizontal privilege escalation

2. Broken User Authentication
   - Test weak password policies
   - Verify JWT token validation
   - Test session management flaws

3. Excessive Data Exposure
   - Verify response data filtering
   - Test for sensitive data leakage
   - Check API versioning security

4. Lack of Resources & Rate Limiting
   - Test for DoS vulnerability
   - Verify rate limiting implementation
   - Test resource consumption attacks

5. Broken Function Level Authorization
   - Test vertical privilege escalation
   - Verify role-based access controls
   - Test administrative function access

Security Testing Framework:
```typescript
describe('API Security Tests', () => {
  describe('Authentication Security', () => {
    test('should reject requests with invalid JWT tokens', async () => {
      const invalidToken = 'invalid.jwt.token';
      const response = await request(app)
        .get('/api/users/profile')
        .set('Authorization', `Bearer ${invalidToken}`)
        .expect(401);
      
      expect(response.body.error).toBe('Invalid token');
    });
    
    test('should reject expired JWT tokens', async () => {
      const expiredToken = generateExpiredToken();
      const response = await request(app)
        .get('/api/users/profile')
        .set('Authorization', `Bearer ${expiredToken}`)
        .expect(401);
      
      expect(response.body.error).toBe('Token expired');
    });
  });
  
  describe('Authorization Security', () => {
    test('should prevent access to other users data (BOLA)', async () => {
      const userToken = await generateUserToken('user1');
      const response = await request(app)
        .get('/api/users/user2/profile')
        .set('Authorization', `Bearer ${userToken}`)
        .expect(403);
      
      expect(response.body.error).toBe('Access denied');
    });
  });
});
```

Include comprehensive test cases for:
- Input validation and sanitization
- SQL injection prevention
- XSS prevention
- CSRF protection
- Mass assignment prevention
- Business logic vulnerability testing
- API versioning security
- Logging and monitoring verification
```

---

## ⚡ Advanced Performance Testing with Grafana K6

### Comprehensive Performance Testing Strategy
```
Design a comprehensive performance testing strategy using Grafana K6:

Application Architecture Analysis:
- Frontend: [NextJS/React] with [SSR/CSR/SSG]
- Backend: [Node.js/Java/Python] microservices
- Database: [PostgreSQL/MongoDB] with [connection pooling]
- Caching: [Redis/Memcached] distributed cache
- CDN: [CloudFlare/AWS CloudFront] for static assets
- Load Balancer: [ALB/Nginx] with health checks
- Infrastructure: [AWS/Azure/GCP] with auto-scaling

Performance Requirements:
- SLA Targets: 99.9% availability, <2s response time
- Load Patterns: Peak 10,000 concurrent users
- Throughput: 50,000 requests/minute
- Geographic Distribution: Global user base
- Device Types: 60% mobile, 40% desktop
- Browser Mix: Chrome 70%, Safari 20%, Firefox 10%

K6 Testing Strategy:
1. Smoke Testing (1-10 users, 2-5 minutes)
2. Load Testing (average load, 10-30 minutes)
3. Stress Testing (above normal load, find breaking point)
4. Spike Testing (sudden load increases)
5. Volume Testing (large amounts of data)
6. Soak Testing (extended periods, memory leaks)
7. Breakpoint Testing (gradually increase until failure)

Provide:
- K6 script architecture and organization
- Test data management strategy
- Environment setup and CI/CD integration
- Monitoring and alerting configuration
- Performance baseline establishment
- Bottleneck identification methodology
```

### 🚀 Grafana K6 Implementation Examples

#### Advanced K6 Performance Testing Framework
```
Create a comprehensive K6 testing framework for a modern web application:

Framework Structure:
```javascript
// k6-framework/
// ├── config/
// │   ├── environments.js
// │   └── thresholds.js
// ├── data/
// │   ├── users.json
// │   └── products.json
// ├── scenarios/
// │   ├── smoke.js
// │   ├── load.js
// │   ├── stress.js
// │   └── spike.js
// ├── utils/
// │   ├── auth.js
// │   ├── checks.js
// │   └── metrics.js
// └── tests/
//     ├── api/
//     └── ui/
```

Main Test Configuration:
```javascript
import http from 'k6/http';
import { check, sleep, group } from 'k6';
import { SharedArray } from 'k6/data';
import { Counter, Rate, Trend } from 'k6/metrics';
import { htmlReport } from 'https://raw.githubusercontent.com/benc-uk/k6-reporter/main/dist/bundle.js';

// Custom metrics
const customErrorRate = new Rate('custom_error_rate');
const customResponseTime = new Trend('custom_response_time');
const apiCallsCounter = new Counter('api_calls_total');

// Test data
const users = new SharedArray('users', function () {
  return JSON.parse(open('./data/users.json'));
});

// Test scenarios
export const options = {
  scenarios: {
    smoke: {
      executor: 'constant-vus',
      vus: 2,
      duration: '2m',
      tags: { test_type: 'smoke' },
    },
    load: {
      executor: 'ramping-vus',
      startVUs: 0,
      stages: [
        { duration: '5m', target: 100 },
        { duration: '10m', target: 100 },
        { duration: '5m', target: 0 },
      ],
      tags: { test_type: 'load' },
    },
    stress: {
      executor: 'ramping-vus',
      startVUs: 0,
      stages: [
        { duration: '5m', target: 200 },
        { duration: '10m', target: 500 },
        { duration: '5m', target: 0 },
      ],
      tags: { test_type: 'stress' },
    },
  },
  thresholds: {
    http_req_duration: ['p(95)<2000'], // 95% of requests under 2s
    http_req_failed: ['rate<0.1'],     // Error rate under 10%
    custom_error_rate: ['rate<0.05'],
  },
};

export default function () {
  // Test implementation
}

export function handleSummary(data) {
  return {
    'summary.html': htmlReport(data),
    'summary.json': JSON.stringify(data, null, 2),
  };
}
```

Requirements:
- Realistic user behavior simulation
- Advanced metrics collection
- Custom assertions and validations
- Environment-specific configuration
- Integration with monitoring systems
- Automated performance regression detection
- CI/CD pipeline integration
- Custom reporting and dashboards
```

#### E-commerce Application Performance Testing
```
Create comprehensive K6 performance tests for an e-commerce platform:

User Journey Scenarios:
1. Guest User Journey (40% of traffic)
   - Browse homepage
   - Search for products
   - View product details
   - Add items to cart
   - Checkout as guest

2. Registered User Journey (35% of traffic)
   - Login to account
   - Browse personalized recommendations
   - Add items to cart
   - Apply coupon codes
   - Complete purchase

3. Admin User Journey (5% of traffic)
   - Admin dashboard access
   - Product management operations
   - Order processing
   - Analytics review

4. API-Only Traffic (20% of traffic)
   - Mobile app API calls
   - Third-party integrations
   - Webhook notifications
   - Background data synchronization

K6 Implementation:
```javascript
import http from 'k6/http';
import { check, sleep, group } from 'k6';
import { SharedArray } from 'k6/data';
import { Rate, Trend, Counter } from 'k6/metrics';

// Performance metrics
const checkoutErrorRate = new Rate('checkout_errors');
const searchResponseTime = new Trend('search_response_time');
const apiSuccessRate = new Rate('api_success_rate');

export const options = {
  scenarios: {
    guest_users: {
      executor: 'ramping-vus',
      startVUs: 0,
      stages: [
        { duration: '2m', target: 40 },
        { duration: '10m', target: 40 },
        { duration: '2m', target: 0 },
      ],
      exec: 'guestUserJourney',
    },
    registered_users: {
      executor: 'ramping-vus',
      startVUs: 0,
      stages: [
        { duration: '2m', target: 35 },
        { duration: '10m', target: 35 },
        { duration: '2m', target: 0 },
      ],
      exec: 'registeredUserJourney',
    },
    api_traffic: {
      executor: 'constant-arrival-rate',
      rate: 100,
      timeUnit: '1s',
      duration: '14m',
      preAllocatedVUs: 20,
      exec: 'apiTraffic',
    },
  },
  thresholds: {
    'http_req_duration{scenario:guest_users}': ['p(95)<3000'],
    'http_req_duration{scenario:registered_users}': ['p(95)<2500'],
    'http_req_duration{scenario:api_traffic}': ['p(95)<1000'],
    checkout_errors: ['rate<0.01'],
    api_success_rate: ['rate>0.99'],
  },
};

export function guestUserJourney() {
  group('Guest User - Product Discovery', () => {
    // Homepage visit
    let response = http.get('https://api.example.com/');
    check(response, {
      'homepage loads successfully': (r) => r.status === 200,
      'homepage response time OK': (r) => r.timings.duration < 2000,
    });
    
    sleep(2);
    
    // Product search
    response = http.get('https://api.example.com/api/products/search?q=laptop&limit=20');
    searchResponseTime.add(response.timings.duration);
    check(response, {
      'search returns results': (r) => r.json('products').length > 0,
    });
    
    sleep(3);
  });
  
  group('Guest User - Checkout Process', () => {
    // Add to cart
    const cartData = {
      productId: 'prod_123',
      quantity: 1,
      sessionId: `session_${__VU}_${__ITER}`,
    };
    
    response = http.post('https://api.example.com/api/cart/add', JSON.stringify(cartData), {
      headers: { 'Content-Type': 'application/json' },
    });
    
    const checkoutSuccess = check(response, {
      'add to cart successful': (r) => r.status === 200,
    });
    
    checkoutErrorRate.add(!checkoutSuccess);
    sleep(5);
  });
}

export function apiTraffic() {
  // Mobile API simulation
  const apiResponse = http.get('https://api.example.com/api/v2/products/featured', {
    headers: {
      'Accept': 'application/json',
      'User-Agent': 'MobileApp/2.1.0',
    },
  });
  
  const success = check(apiResponse, {
    'API response successful': (r) => r.status === 200,
    'API response time acceptable': (r) => r.timings.duration < 1000,
  });
  
  apiSuccessRate.add(success);
}
```

Performance Monitoring Integration:
- Real-time metrics streaming to Grafana
- Custom dashboards for different scenarios
- Automated alerting on threshold breaches
- Performance regression detection
- Capacity planning recommendations
```

#### Advanced K6 Monitoring and Observability
```
Implement comprehensive monitoring and observability for K6 performance tests:

Monitoring Stack Integration:
```javascript
// k6-monitoring-setup.js
import { check, sleep } from 'k6';
import http from 'k6/http';
import { Trend, Rate, Counter, Gauge } from 'k6/metrics';
import { textSummary } from 'https://jslib.k6.io/k6-summary/0.0.1/index.js';

// Custom Business Metrics
const userRegistrations = new Counter('user_registrations_total');
const orderValue = new Trend('order_value_usd');
const inventoryLevel = new Gauge('inventory_items_available');
const conversionRate = new Rate('checkout_conversion_rate');

// Performance Metrics by Business Function
const loginResponseTime = new Trend('login_response_time');
const searchResponseTime = new Trend('search_response_time');
const checkoutResponseTime = new Trend('checkout_response_time');
const apiResponseTime = new Trend('api_response_time');

export const options = {
  scenarios: {
    performance_monitoring: {
      executor: 'ramping-vus',
      stages: [
        { duration: '5m', target: 50 },
        { duration: '30m', target: 100 },
        { duration: '5m', target: 0 },
      ],
    },
  },
  
  // SLA-based thresholds
  thresholds: {
    // Business SLA requirements
    http_req_duration: [
      'p(50)<1000',   // 50% under 1s
      'p(95)<2000',   // 95% under 2s  
      'p(99)<5000',   // 99% under 5s
    ],
    http_req_failed: ['rate<0.01'],
    
    // Business-specific SLAs
    login_response_time: ['p(95)<1500'],
    search_response_time: ['p(95)<800'],
    checkout_response_time: ['p(95)<3000'],
    checkout_conversion_rate: ['rate>0.85'],
  },
  
  // External monitoring integration
  ext: {
    loadimpact: {
      // Grafana Cloud k6 integration
      projectID: 12345,
      name: 'E-commerce Performance Test',
    },
  },
};

export default function () {
  group('Business Transaction Monitoring', () => {
    // User login with business metrics
    let response = http.post('https://api.example.com/api/auth/login', {
      email: 'test@example.com',
      password: 'password123',
    });
    
    loginResponseTime.add(response.timings.duration);
    
    if (check(response, { 'login successful': (r) => r.status === 200 })) {
      userRegistrations.add(1);
    }
    
    // Product search with performance tracking
    response = http.get('https://api.example.com/api/search?q=electronics');
    searchResponseTime.add(response.timings.duration);
    
    // Simulate checkout process
    const checkoutData = generateCheckoutData();
    response = http.post('https://api.example.com/api/checkout', checkoutData);
    checkoutResponseTime.add(response.timings.duration);
    
    if (check(response, { 'checkout successful': (r) => r.status === 201 })) {
      conversionRate.add(1);
      orderValue.add(checkoutData.totalAmount);
    } else {
      conversionRate.add(0);
    }
  });
  
  sleep(1);
}

// Custom summary with business metrics
export function handleSummary(data) {
  console.log('Performance Test Summary:');
  console.log(`- Total Users Simulated: ${data.metrics.vus_max.values.max}`);
  console.log(`- Test Duration: ${data.state.testRunDurationMs / 1000}s`);
  console.log(`- Total Requests: ${data.metrics.http_reqs.values.count}`);
  console.log(`- Error Rate: ${(data.metrics.http_req_failed.values.rate * 100).toFixed(2)}%`);
  
  return {
    'stdout': textSummary(data, { indent: ' ', enableColors: true }),
    'summary.json': JSON.stringify(data, null, 2),
    'business-metrics.json': JSON.stringify({
      userRegistrations: data.metrics.user_registrations_total?.values.count || 0,
      averageOrderValue: data.metrics.order_value_usd?.values.avg || 0,
      conversionRate: data.metrics.checkout_conversion_rate?.values.rate || 0,
    }, null, 2),
  };
}

function generateCheckoutData() {
  return {
    items: [
      { productId: 'prod_123', quantity: 1, price: 99.99 },
    ],
    totalAmount: 99.99,
    paymentMethod: 'credit_card',
    shippingAddress: {
      street: '123 Test St',
      city: 'Test City',
      zipCode: '12345',
    },
  };
}
```

Grafana Dashboard Configuration:
- Real-time performance metrics visualization
- Business KPI tracking during load tests
- SLA compliance monitoring
- Resource utilization correlation
- Automated anomaly detection
- Performance trend analysis
- Capacity planning insights

CI/CD Integration:
- Automated performance regression detection
- Performance budgets enforcement
- Load test orchestration in pipelines
- Performance report generation
- Stakeholder notifications
- Environment-specific test execution
```

---

## 🔒 Security Testing

### Security Testing Templates

#### Security Test Planning
```
Create a security testing plan for [application type]:

Application Details:
- Authentication method: [method]
- User roles and permissions: [list]
- Sensitive data handled: [types]
- External integrations: [systems]

Security tests needed:
1. Authentication and session management
2. Input validation and sanitization
3. Authorization and access controls
4. Data encryption verification
5. Error handling security
6. Business logic vulnerabilities

For each category, provide:
- Specific test cases
- Testing tools recommendations
- Risk assessment criteria
- Remediation priorities
```

#### OWASP Top 10 Test Cases
```
Generate test cases for OWASP Top 10 vulnerabilities for a web application:

Application: [brief description]
Authentication: [method used]
Technology Stack: [technologies]

For each OWASP Top 10 category, provide:
1. Specific test scenarios
2. Testing techniques
3. Tools to use (manual and automated)
4. Evidence collection methods
5. Risk rating criteria

Focus on practical, actionable test cases that can be executed by QA team.
```

---

## 📊 Test Data Management

### Test Data Generation Templates

#### Synthetic Test Data Creation
```
Generate realistic test data for [application] testing:

Data Requirements:
- User profiles: [number needed] with realistic names, emails, addresses
- Product catalog: [number] items with categories, prices, descriptions  
- Transaction history: [number] orders with realistic patterns
- Date ranges: [specify periods]

Data Characteristics:
- Geographic distribution: [regions]
- Demographic variety: [age groups, preferences]
- Business scenarios: [edge cases to include]

Output formats: CSV, JSON, SQL INSERT statements
Include data relationships and referential integrity.
```

#### Data Masking Strategy
```
Design a data masking strategy for production data used in testing:

Sensitive Data Types:
- Personal information: [PII types]
- Financial data: [types]
- Healthcare data: [if applicable]
- Business confidential: [types]

Requirements:
- Maintain data relationships
- Preserve data format and structure
- Support realistic testing scenarios
- Comply with [regulations - GDPR, HIPAA, etc.]

Recommend:
1. Masking techniques for each data type
2. Tools and technologies
3. Implementation approach
4. Validation methods
5. Governance processes
```

---

## 📋 Documentation & Reporting

### Test Documentation Templates

#### Test Strategy Document
```
Create a comprehensive test strategy document for [project]:

Project Overview:
- Scope: [features to test]
- Timeline: [testing phases]
- Team: [team composition]
- Budget: [constraints]

Document should include:
1. Testing approach and methodology
2. Test levels and types
3. Entry and exit criteria
4. Risk assessment and mitigation
5. Test environment requirements
6. Defect management process
7. Communication plan
8. Success metrics and KPIs

Format as professional document suitable for stakeholder review.
```

#### Test Execution Report
```
Generate a test execution summary report template:

Report Period: [dates]
Testing Phase: [phase name]
Application: [name and version]

Include sections for:
1. Executive summary
2. Test execution metrics (passed/failed/blocked)
3. Defect summary with severity breakdown
4. Test coverage analysis
5. Risk assessment of remaining issues
6. Recommendations for release decision
7. Lessons learned and process improvements

Make it suitable for both technical team and management audience.
```

---

## 🎯 Advanced QA Prompts

### Test Case Review and Optimization
```
Review and optimize these existing test cases:

[Paste existing test cases]

Analyze for:
1. Completeness of coverage
2. Redundancy elimination
3. Priority and risk-based ordering
4. Maintainability improvements
5. Automation potential
6. Data-driven opportunities

Provide specific recommendations with rationale.
```

### Exploratory Testing Guidance
```
Design an exploratory testing session for [feature]:

Feature: [description]
Time Available: [duration]
Testing Focus: [areas of concern]
User Personas: [target users]

Provide:
1. Testing charter with clear objectives
2. Risk-based testing areas to explore
3. User journey scenarios to investigate
4. Tools and techniques to use
5. Documentation approach
6. Session debrief template
```

### Test Metrics Analysis
```
Analyze these testing metrics and provide insights:

Metrics Data:
- Test execution rate: [data]
- Defect detection rate: [data]
- Test coverage: [data]
- Automation coverage: [data]
- Defect leakage: [data]

Provide:
1. Trend analysis and patterns
2. Quality insights and risks
3. Process improvement recommendations
4. Benchmarking against industry standards
5. Action items with priorities
```

---

## 🚀 QA Productivity Tips

### 1. **Batch Similar Prompts**
Generate multiple related test cases in one request:
```
"Create test cases for login, registration, and password reset features"
```

### 2. **Use Templates Consistently**
Develop standard prompt templates for recurring tasks

### 3. **Include Context Always**
- Application type and technology
- User personas and business context
- Risk levels and priorities
- Constraints and limitations

### 4. **Ask for Multiple Formats**
```
"Provide test cases in both Gherkin format and traditional test case format"
```

### 5. **Request Prioritization**
```
"Order test cases by risk level and business impact"
```

---

## 📚 Ready-to-Use QA Templates

### Quick Testing Tasks

#### Smoke Test Suite
```
Generate a smoke test suite for [application] covering:
- Core functionality verification
- Critical user paths
- System integration points
- Data integrity checks
- Performance baseline verification

Time limit: 30 minutes execution
Format: Checklist with pass/fail criteria
```

#### Regression Test Planning
```
Plan regression testing for [feature change]:

Change Description: [what changed]
Impact Analysis: [affected areas]
Risk Assessment: [high/medium/low risks]

Recommend:
1. Regression test scope
2. Test selection criteria
3. Automation vs manual split
4. Timeline and resources needed
5. Success criteria
```

---

<div align="center">

### 🎯 Elevate Your QA Excellence

<table>
<tr>
<td align="center" width="33%">

**⚡ Test Templates**

<a href="../../templates/">
<img src="https://img.shields.io/badge/Get_Templates-Test_Now-FF6B6B?style=for-the-badge" alt="Templates"/>
</a>

*Ready-to-use test prompts*

</td>
<td align="center" width="33%">

**🚀 Advanced QA**

<a href="../../techniques/advanced/">
<img src="https://img.shields.io/badge/Advanced_Techniques-Master-4ECDC4?style=for-the-badge" alt="Advanced"/>
</a>

*Sophisticated testing*

</td>
<td align="center" width="33%">

**💡 QA Examples**

<a href="../../examples/">
<img src="https://img.shields.io/badge/Browse_Examples-Learn-45B7D1?style=for-the-badge" alt="Examples"/>
</a>

*Real testing scenarios*

</td>
</tr>
</table>

</div>

---

<div align="center">

**🧪 Quality Testing with AI Power!**

<p><em>Transform your QA workflow - comprehensive testing, faster analysis, better quality</em></p>

<sub>🏠 <a href="../../">← Back to Main Guide</a> | 💻 <a href="../developers/">Dev Guide →</a> | 💼 <a href="../business-users/">Business Guide →</a></sub>

</div>