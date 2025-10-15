# 🤖 AI Development Prompts for TestBeforeExam

## � CRITICAL AI INSTRUCTIONS

### **NEVER CREATE NEW FILES - UPDATE EXISTING ONES**
When working on TestBeforeExam:
- **NO new .md files**: Never create context files, config files, or additional documentation
- **Update existing files**: Only modify README.md, INSTRUCTIONS.md, PROMPTS.md, CONTRIBUTING.md
- **One source of truth**: Each piece of information has ONE location
- **Enhance, don't duplicate**: Always improve existing content instead of creating new files

### **File Update Rules**
- Technical specs → Update README.md architecture section
- Development guidelines → Update INSTRUCTIONS.md
- New prompts/patterns → Update this PROMPTS.md file
- Contribution workflows → Update CONTRIBUTING.md
- **Never suggest creating**: .ai-context.md, .cursorrules, docs/ folder, or any additional files

## �📋 Prompt Categories

### 🏗️ Architecture & Planning Prompts
### 💻 Development Prompts  
### 📊 Data Management Prompts
### 🎨 UI/UX Design Prompts
### 🧪 Testing & Quality Prompts
### 🚀 Deployment & DevOps Prompts
### 📈 Analytics & Optimization Prompts

---

## 🏗️ Architecture & Planning Prompts

### System Architecture Analysis
```
Analyze the current TestBeforeExam repository structure and suggest improvements for:
1. Scalability for handling 10,000+ questions
2. Performance optimization for mobile and web apps
3. Free hosting solutions that can handle moderate traffic
4. Data organization for multiple exam types and subjects
5. API design that leverages GitHub as a database

Current constraints:
- Must use free services only
- GitHub repository as primary data source
- Support for web and mobile applications
- Minimal hosting costs

Provide specific recommendations with implementation steps.
```

### Technology Stack Optimization
```
Given the goal of creating a free, efficient exam preparation platform, evaluate and recommend:
1. Frontend frameworks (React, Vue, Svelte) for web app
2. Mobile development approach (React Native, Flutter, PWA)
3. State management solutions
4. Build tools and bundlers
5. Free CDN and hosting options

Consider:
- Bundle size optimization
- Performance on low-end devices
- Offline capability requirements
- Cross-platform compatibility

Provide a detailed comparison with pros/cons for each option.
```

---

## 💻 Development Prompts

### Component Development
```
Create a [COMPONENT_TYPE] component for the TestBeforeExam app with the following requirements:
- Component Name: [COMPONENT_NAME]
- Functionality: [SPECIFIC_FUNCTIONALITY]
- Props/Parameters: [LIST_PROPS]
- State Requirements: [STATE_NEEDS]
- Performance Considerations: [PERFORMANCE_NOTES]

Technical Requirements:
- TypeScript support
- Responsive design
- Accessibility compliance
- Unit test coverage
- Error handling
- Loading states

Please provide:
1. Component implementation
2. TypeScript interfaces
3. CSS/styling approach
4. Unit tests
5. Usage examples
6. Performance optimization notes
```

### API Integration Pattern
```
Design and implement an API integration pattern for fetching exam questions from GitHub repository:

Requirements:
- Source: GitHub raw content API
- Caching strategy for performance
- Error handling and retry logic
- Offline support capability
- Data validation
- Rate limiting considerations

Data Structure:
- Questions organized by subject/topic
- Multiple question formats support
- Metadata for filtering and search
- Version control for content updates

Provide:
1. API service implementation
2. Caching mechanism
3. Error handling strategy
4. TypeScript interfaces
5. Integration examples
```

### Shared Logic Development
```
Create shared utility functions for the TestBeforeExam platform:

Function Category: [CATEGORY] (e.g., question-processing, user-progress, scoring)
Specific Functions Needed: [LIST_FUNCTIONS]

Requirements:
- Platform agnostic (web + mobile)
- TypeScript implementation
- Comprehensive error handling
- Unit test coverage
- Performance optimized
- Well documented

For each function provide:
1. Implementation with TypeScript
2. Input/output interfaces
3. Error scenarios handling
4. Unit tests
5. Performance considerations
6. Usage examples
```

---

## 📊 Data Management Prompts

### Question Schema Design
```
Design a comprehensive JSON schema for exam questions that supports:

Question Types:
- Multiple choice (single/multiple answers)
- True/False
- Fill in the blanks
- Essay/descriptive
- Image-based questions
- Code/programming questions

Metadata Requirements:
- Subject categorization
- Difficulty levels
- Exam type associations
- Learning objectives
- Time estimates
- Prerequisites

Validation Requirements:
- Required field validation
- Data type checking
- Content length limits
- Format consistency
- Relationship integrity

Provide:
1. Complete JSON schema
2. Validation rules
3. Example question objects
4. Migration strategy for schema updates
5. Optimization for file size
```

### Content Organization Strategy
```
Develop a file organization strategy for managing thousands of exam questions:

Current Requirements:
- [NUMBER] subjects with [NUMBER] topics each
- Support for [EXAM_TYPES]
- Easy content discovery and updates
- Git-friendly file structure
- Performance optimized loading

Constraints:
- GitHub repository limits
- Mobile app bundle size
- Web app performance
- Search and filtering needs
- Content contribution workflow

Provide:
1. Directory structure proposal
2. File naming conventions
3. Content splitting strategy
4. Index/manifest generation
5. Search optimization approach
6. Content validation workflow
```

### Data Migration Tools
```
Create tools for managing question data in the TestBeforeExam repository:

Tool Requirements:
1. Content validation and linting
2. Format conversion (CSV/Excel to JSON)
3. Bulk operations (update, delete, merge)
4. Schema migration utilities
5. Content deduplication
6. Quality assurance checks

Technical Specifications:
- Node.js/TypeScript implementation
- CLI interface with clear commands
- Batch processing capabilities
- Progress reporting
- Error handling and rollback
- Integration with CI/CD pipeline

For each tool provide:
1. Implementation code
2. CLI interface design
3. Configuration options
4. Error handling strategy
5. Usage documentation
6. Integration examples
```

---

## 🎨 UI/UX Design Prompts

### User Interface Components
```
Design a [COMPONENT_TYPE] for the exam taking interface:

Component: [SPECIFIC_COMPONENT] (e.g., Question Display, Progress Indicator, Result Summary)
Target Users: [USER_TYPE] (Students, Teachers, General Public)
Device Targets: [DEVICES] (Mobile, Tablet, Desktop)

Requirements:
- Intuitive and accessible design
- Consistent with modern UI patterns
- Performance optimized
- Responsive across screen sizes
- Dark/light theme support
- Internationalization ready

Provide:
1. Component design specification
2. CSS/styling implementation
3. Responsive behavior details
4. Accessibility considerations
5. Animation and interaction patterns
6. Theme integration approach
```

### User Experience Flow
```
Design the complete user journey for [USER_SCENARIO]:

Scenario: [SPECIFIC_SCENARIO] (e.g., Taking a practice exam, Reviewing results, Contributing questions)
User Type: [USER_PROFILE]
Entry Point: [WHERE_USER_STARTS]
Success Criteria: [WHAT_SUCCESS_LOOKS_LIKE]

Consider:
- User motivation and goals
- Potential friction points
- Mobile vs desktop differences
- Accessibility requirements
- Performance constraints
- Offline scenarios

Provide:
1. Step-by-step user flow
2. Wireframes or mockups
3. Interaction patterns
4. Error states and recovery
5. Performance considerations
6. Analytics tracking points
```

---

## 🧪 Testing & Quality Prompts

### Test Strategy Development
```
Create a comprehensive testing strategy for TestBeforeExam:

Application Components:
- [LIST_COMPONENTS_TO_TEST]
- Data processing functions
- API integrations
- UI components
- User workflows

Testing Types Required:
- Unit tests
- Integration tests
- End-to-end tests
- Performance tests
- Accessibility tests
- Cross-browser testing

Constraints:
- Free testing tools only
- CI/CD integration
- Mobile and web coverage
- Automated execution

Provide:
1. Testing framework recommendations
2. Test structure and organization
3. Mock and fixture strategies
4. CI/CD integration approach
5. Coverage requirements
6. Performance benchmarks
```

### Quality Assurance Automation
```
Design automated quality assurance for question content:

Validation Requirements:
- Question format correctness
- Answer accuracy verification
- Content appropriateness check
- Difficulty level consistency
- Duplicate detection
- Metadata completeness

Automation Goals:
- Pre-commit validation
- Continuous integration checks
- Contributor feedback
- Quality scoring system
- Performance impact assessment

Technical Approach:
- Node.js/TypeScript tools
- GitHub Actions integration
- Configurable rule engine
- Detailed error reporting
- Performance optimization

Provide:
1. Validation rule engine
2. Automation workflow
3. Error reporting system
4. Configuration management
5. Integration with Git hooks
6. Performance monitoring
```

---

## 🚀 Deployment & DevOps Prompts

### CI/CD Pipeline Design
```
Design a complete CI/CD pipeline for TestBeforeExam using free services:

Repository Events:
- Push to main branch
- Pull request creation
- Content updates
- Release tagging

Pipeline Stages:
1. Code quality checks
2. Automated testing
3. Build optimization
4. Deployment to staging
5. Production deployment
6. Performance monitoring

Free Tools Available:
- GitHub Actions
- Netlify/Vercel deployment
- Various free monitoring services

Requirements:
- Fast build times
- Reliable deployments
- Rollback capabilities
- Environment management
- Secret management

Provide:
1. Complete workflow files
2. Build optimization strategies
3. Deployment configurations
4. Monitoring setup
5. Troubleshooting guides
```

### Performance Optimization
```
Optimize the TestBeforeExam application for maximum performance:

Target Metrics:
- Load time < 3 seconds
- First Contentful Paint < 1.5 seconds
- Largest Contentful Paint < 2.5 seconds
- Cumulative Layout Shift < 0.1
- First Input Delay < 100ms

Optimization Areas:
- Bundle size reduction
- Image optimization
- Caching strategies
- Code splitting
- Service worker implementation
- CDN utilization

Constraints:
- Free hosting limitations
- Mobile device performance
- Offline capability
- SEO requirements

Provide:
1. Performance audit checklist
2. Optimization implementation
3. Monitoring and measurement
4. Progressive enhancement strategy
5. Fallback mechanisms
```

---

## 📈 Analytics & Optimization Prompts

### Analytics Implementation
```
Implement comprehensive analytics for TestBeforeExam using free tools:

Metrics to Track:
- User engagement patterns
- Question difficulty analysis
- Popular subjects and topics
- Completion rates
- Performance insights
- Error tracking

Privacy Requirements:
- GDPR compliance
- User consent management
- Data anonymization
- Minimal data collection

Free Tools Integration:
- Google Analytics 4
- GitHub Insights
- Web Vitals monitoring
- Custom event tracking

Provide:
1. Analytics implementation code
2. Event tracking strategy
3. Dashboard setup
4. Privacy compliance measures
5. Data interpretation guidelines
6. Automated reporting system
```

### A/B Testing Framework
```
Create a lightweight A/B testing framework for optimizing user experience:

Testing Scenarios:
- Question presentation formats
- User interface variations
- Navigation patterns
- Content organization
- Call-to-action placement

Technical Requirements:
- Client-side implementation
- No external dependencies
- Privacy compliant
- Performance minimal impact
- Statistical significance tracking

Implementation Constraints:
- Small bundle size impact
- Easy configuration
- Results analysis tools
- Integration with analytics

Provide:
1. A/B testing framework code
2. Configuration management
3. Statistical analysis tools
4. Integration examples
5. Best practices guide
6. Results interpretation
```

---

## 🔄 Self-Evolution System

### Prompt Enhancement Process
```
This prompts file should evolve based on:

1. **Project Development Phases**
   - Add new prompt categories as features develop
   - Refine existing prompts based on outcomes
   - Remove outdated or ineffective prompts

2. **Community Feedback**
   - Incorporate contributor suggestions
   - Address common development challenges
   - Add prompts for frequently needed tasks

3. **Technology Updates**
   - Update tool recommendations
   - Add new framework integrations
   - Reflect modern development practices

4. **Performance Insights**
   - Add prompts for identified bottlenecks
   - Include optimization strategies that work
   - Remove approaches that prove ineffective

Evolution Triggers:
- Major feature additions
- Technology stack changes
- Performance improvements needed
- Community contribution patterns
- User feedback insights
```

### Prompt Usage Analytics
```
Track the effectiveness of these prompts:

Metrics to Monitor:
- Which prompts are used most frequently
- Success rate of prompt outcomes
- Time saved in development tasks
- Quality of generated solutions
- Community adoption rates

Feedback Collection:
- Developer experience surveys
- Code review quality assessments
- Performance impact measurements
- Bug reduction analysis
- Development velocity tracking

Continuous Improvement:
- Regular prompt review and update cycles
- A/B testing of prompt variations
- Community input on prompt effectiveness
- Integration of lessons learned
```

---

## 📚 Prompt Usage Guidelines

### Effective Prompt Usage
1. **Be Specific**: Include exact requirements and constraints
2. **Provide Context**: Share relevant project details and current state
3. **Set Clear Goals**: Define success criteria and expected outcomes
4. **Include Examples**: Reference existing code or desired patterns
5. **Consider Constraints**: Mention limitations and requirements

### Customization Template
```
When using these prompts, customize the bracketed placeholders:
- [COMPONENT_NAME]: Specific component you're working on
- [FUNCTIONALITY]: Exact feature requirements
- [USER_TYPE]: Target audience characteristics
- [CONSTRAINTS]: Technical or business limitations
- [TIMELINE]: Development time expectations

Example customization:
Original: "Create a [COMPONENT_TYPE] component..."
Customized: "Create a question display component for math equations with LaTeX rendering support..."
```

---

## 📝 Evolution Log
| Date | Version | Changes | Usage Context |
|------|---------|---------|---------------|
| 2025-10-15 | 1.0.0 | Initial prompt collection created | Project foundation |

**Auto-Update Reminder**: This file should be reviewed and updated monthly or when major project milestones are reached. Each evolution should improve prompt effectiveness and add value for developers and contributors.