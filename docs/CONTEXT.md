# 🏗️ Project Architecture & Context

## 📍 Project Overview
**TestBeforeExam** is a free, open-source exam preparation platform that uses GitHub as a database and leverages free hosting services to provide high-quality practice tests to students worldwide.

## 🎯 AI Assistant Context
This file provides essential context for AI assistants working on this project.

### Core Principles
- **Free First**: Every solution must use free services
- **GitHub as Database**: Repository serves as the primary data source
- **Performance Optimized**: Fast loading, mobile-friendly
- **Community Driven**: Open for contributions and improvements
- **Accessibility Focused**: Inclusive design for all users

### Technology Stack
- **Frontend**: React with TypeScript
- **Mobile**: React Native (Expo)
- **Hosting**: Netlify/Vercel (free tier)
- **CDN**: jsDelivr for content delivery
- **Database**: GitHub repository (JSON files)
- **CI/CD**: GitHub Actions

## 📁 Repository Structure
```
TestBeforeExam/
├── README.md                 # Main project documentation
├── INSTRUCTIONS.md           # Detailed project guidelines
├── PROMPTS.md               # AI development prompts
├── CONTRIBUTING.md          # Contribution guidelines
├── LICENSE                  # MIT License
├── .github/                 # GitHub configuration
│   ├── workflows/           # CI/CD workflows
│   ├── ISSUE_TEMPLATE/      # Issue templates
│   └── PULL_REQUEST_TEMPLATE.md
├── docs/                    # Documentation
│   ├── CONTEXT.md          # This file - AI context
│   ├── ARCHITECTURE.md     # System architecture
│   ├── API.md              # API documentation
│   └── DEPLOYMENT.md       # Deployment guide
├── data/                   # Question data
│   ├── subjects/           # Organized by subject
│   ├── schemas/            # Data validation schemas
│   └── index.json          # Content index
├── apps/                   # Application code
│   ├── web/               # Web application
│   ├── mobile/            # Mobile application
│   └── shared/            # Shared utilities
└── tools/                 # Development tools
    ├── validators/        # Content validation
    ├── generators/        # Content generators
    └── scripts/           # Utility scripts
```

## 🤖 AI Assistant Guidelines

### Development Context
When working on this project, always consider:
1. **Free Infrastructure**: Solutions must use free services
2. **Performance**: Optimize for mobile and low-bandwidth users
3. **Accessibility**: Follow WCAG guidelines
4. **Scalability**: Design for thousands of questions
5. **Community**: Enable easy contributions

### Key Files to Reference
- `INSTRUCTIONS.md` - Comprehensive project guidelines
- `PROMPTS.md` - Development prompts and patterns
- `CONTRIBUTING.md` - Contribution workflows
- `data/schemas/` - Data structure definitions

### Common Tasks
1. **Adding Questions**: Follow schema in `data/schemas/`
2. **UI Components**: Use TypeScript, responsive design
3. **API Changes**: Update documentation in `docs/API.md`
4. **Performance**: Consider bundle size and loading times
5. **Testing**: Include unit and integration tests

## 📊 Data Architecture

### Question Schema
```json
{
  "id": "unique-id",
  "subject": "mathematics",
  "topic": "algebra", 
  "difficulty": "medium",
  "examTypes": ["SAT", "GRE"],
  "question": "Question text",
  "options": ["A", "B", "C", "D"],
  "correctAnswer": 0,
  "explanation": "Detailed explanation",
  "metadata": {
    "contributor": "username",
    "verified": true
  }
}
```

### Content Organization
- Hierarchical: Subject → Topic → Subtopic
- Flexible tagging system
- Multiple exam type support
- Version controlled content

## 🚀 Development Workflow

### 1. Setup
- Node.js environment
- TypeScript configuration
- Testing framework setup
- Linting and formatting

### 2. Development
- Component-driven development
- TypeScript for type safety
- Responsive design principles
- Performance monitoring

### 3. Testing
- Unit tests for functions
- Integration tests for components
- E2E tests for user flows
- Content validation tests

### 4. Deployment
- Automated via GitHub Actions
- Free hosting on Netlify/Vercel
- CDN for global content delivery
- Performance monitoring

## 🎯 Current Priorities

### Phase 1 (Foundation)
- [ ] Basic web application structure
- [ ] Question display and navigation
- [ ] Content management system
- [ ] Mobile responsiveness

### Phase 2 (Features)
- [ ] User progress tracking
- [ ] Advanced search and filtering
- [ ] Offline support
- [ ] Performance optimizations

### Phase 3 (Growth)
- [ ] Community features
- [ ] Analytics dashboard
- [ ] AI-powered recommendations
- [ ] Multi-language support

## 🔧 Development Tools

### Required
- Node.js (v16+)
- TypeScript
- React/React Native
- Git

### Recommended
- VS Code with extensions
- GitHub CLI
- Performance monitoring tools
- Accessibility testing tools

## 📈 Success Metrics

### Technical
- Load time < 3 seconds
- Bundle size < 500KB gzipped
- 95%+ test coverage
- Accessibility compliance

### User
- Question accuracy > 95%
- User engagement > 10 min/session
- Mobile usage > 60%
- Community contributions growing

## 🤝 Community Context

### Contributors
- Students and educators
- Developers and designers
- Subject matter experts
- Quality reviewers

### Contribution Types
- Content (questions, explanations)
- Code (features, bug fixes)
- Design (UI/UX improvements)
- Documentation (guides, tutorials)

## 🔍 AI Assistant Prompts

When working on specific tasks, reference the detailed prompts in `PROMPTS.md`:
- Architecture & Planning
- Development & Coding
- Content Management
- Testing & Quality
- Deployment & DevOps

---

**Last Updated**: October 15, 2025  
**Version**: 1.0.0  
**Maintainer**: Shivaprasadr