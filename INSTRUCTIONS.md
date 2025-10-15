# 📚 TestBeforeExam - Project Instructions

## 🎯 Project Vision
Create a free, efficient, and scalable exam preparation platform that serves questions via GitHub repository, eliminating the need for expensive hosting while maintaining high performance.

## 🏗️ Architecture Philosophy
- **Free & Efficient**: Leverage free services (GitHub, Netlify, Vercel, etc.)
- **Simple & Scalable**: Minimal complexity, maximum efficiency
- **Git-Based Content**: Use GitHub as the primary data source
- **Multi-Platform**: One codebase for web and mobile apps
- **Community-Driven**: Open for contributions and improvements

## 📁 Repository Structure Evolution

### Current Phase (Foundation)
```
TestBeforeExam/
├── README.md                 # Project overview and usage
├── INSTRUCTIONS.md           # This file - project guidelines
├── PROMPTS.md               # AI prompts for project development
├── LICENSE                  # Open source license
├── .github/                 # GitHub workflows and templates
│   ├── workflows/           # CI/CD automation
│   ├── ISSUE_TEMPLATE/      # Issue templates
│   └── PULL_REQUEST_TEMPLATE.md
├── docs/                    # Documentation
│   ├── API.md              # API documentation
│   ├── CONTRIBUTING.md     # Contribution guidelines
│   └── DEPLOYMENT.md       # Deployment instructions
├── data/                   # Exam questions and content
│   ├── subjects/           # Organized by subjects
│   ├── formats/            # Different question formats
│   └── schemas/            # Data validation schemas
├── apps/                   # Application source code
│   ├── web/               # Web application
│   ├── mobile/            # Mobile application
│   └── shared/            # Shared logic and components
└── tools/                 # Development and automation tools
    ├── validators/        # Data validation tools
    ├── generators/        # Content generation tools
    └── scripts/           # Utility scripts
```

### Future Evolution Phases
1. **Phase 1**: Basic structure and core functionality
2. **Phase 2**: Advanced features and optimizations
3. **Phase 3**: Community features and analytics
4. **Phase 4**: AI-powered question generation

## 🔄 Self-Evolution Guidelines

### When to Update This File
- [ ] New major features are added
- [ ] Architecture changes occur
- [ ] New tools or technologies are integrated
- [ ] Community feedback suggests improvements
- [ ] Performance optimizations are implemented

### Evolution Triggers
1. **Repository Growth**: Update structure when new directories are added
2. **Feature Additions**: Document new capabilities and workflows
3. **Community Feedback**: Incorporate suggestions and improvements
4. **Technology Updates**: Reflect changes in tech stack
5. **Performance Insights**: Add optimizations based on usage data

## 🛠️ Development Workflow

### 1. Content Management
- Questions stored in JSON/YAML format
- Categorized by subject, difficulty, and exam type
- Version controlled for change tracking
- Automated validation on commits

### 2. Application Development
- Progressive Web App (PWA) for web
- React Native for mobile (using Expo)
- Shared TypeScript codebase
- Component-driven development

### 3. Deployment Strategy
- **Web App**: Netlify/Vercel (free tier)
- **Mobile App**: Expo for distribution
- **API**: GitHub raw content + GitHub Pages
- **CDN**: jsDelivr for fast content delivery

### 4. Free Infrastructure Stack
- **Repository**: GitHub (free)
- **Hosting**: Netlify/Vercel (free tier)
- **CDN**: jsDelivr (free)
- **CI/CD**: GitHub Actions (free)
- **Analytics**: Google Analytics (free)
- **Monitoring**: UptimeRobot (free)

## 📊 Data Architecture

### Question Format Standard
```json
{
  "id": "unique-question-id",
  "subject": "mathematics",
  "topic": "algebra",
  "difficulty": "medium",
  "examTypes": ["SAT", "GRE"],
  "question": "Question text",
  "options": ["A", "B", "C", "D"],
  "correctAnswer": 0,
  "explanation": "Detailed explanation",
  "tags": ["algebra", "equations"],
  "metadata": {
    "createdAt": "2025-01-01",
    "updatedAt": "2025-01-01",
    "contributor": "username",
    "verified": true
  }
}
```

### Content Organization
- **Hierarchical Structure**: Subject → Topic → Subtopic
- **Difficulty Levels**: Beginner, Intermediate, Advanced
- **Exam Types**: Configurable for different exams
- **Tagging System**: For flexible categorization

## 🚀 Performance Optimization

### Content Delivery
- Lazy loading of questions
- Caching strategies
- Compression (gzip/brotli)
- Image optimization

### Application Performance
- Bundle splitting
- Tree shaking
- Service workers for offline support
- Progressive enhancement

## 🤝 Community Contribution

### Content Contributors
- Subject matter experts
- Educators and teachers
- Students and learners
- Quality reviewers

### Developer Contributors
- Frontend developers
- Mobile developers
- DevOps engineers
- UX/UI designers

## 📈 Analytics and Monitoring

### Key Metrics
- Question accuracy rates
- Popular subjects/topics
- User engagement patterns
- Performance benchmarks

### Free Analytics Tools
- Google Analytics 4
- GitHub Insights
- Netlify Analytics
- Web Vitals monitoring

## 🔒 Data Quality Assurance

### Validation Rules
- Schema validation for all questions
- Content review process
- Automated testing
- Community moderation

### Quality Metrics
- Accuracy verification
- Clarity scoring
- Difficulty calibration
- User feedback integration

## 🎯 Future Roadmap

### Short Term (1-3 months)
- [ ] Basic web application
- [ ] Core question management
- [ ] Initial subject coverage
- [ ] Mobile app MVP

### Medium Term (3-6 months)
- [ ] Advanced features (bookmarks, progress tracking)
- [ ] Multiple exam type support
- [ ] Community contribution system
- [ ] Performance optimizations

### Long Term (6+ months)
- [ ] AI-powered question generation
- [ ] Adaptive learning algorithms
- [ ] Comprehensive analytics dashboard
- [ ] Multi-language support

## 🆘 Getting Help

### Documentation
- Check existing documentation first
- Search through GitHub issues
- Review community discussions

### Support Channels
- GitHub Issues for bugs and features
- GitHub Discussions for questions
- Community forums for general help

---

## 📝 Evolution Log
| Date | Version | Changes | Contributor |
|------|---------|---------|-------------|
| 2025-10-15 | 1.0.0 | Initial instructions created | Project Init |

**Note**: This file should be updated whenever significant changes are made to the project structure, architecture, or goals. Each update should include a new entry in the Evolution Log above.