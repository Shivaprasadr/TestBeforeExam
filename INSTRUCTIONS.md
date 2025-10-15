# 📚 Tes# CDN Access**: https://cdn.jsdelivr.net/gh/Shivaprasadr/TestBeforeExam@main/data/subjects/cloud-computing/aws/

### Live Endpoints (SIMPLIFIED!)
- AWS Certifications Index: `aws/index.json`  
- SAA-C03 All Questions: `aws/saa-c03/questions.json` (single file - all topics!)
- SAA-C03 Metadata: `aws/saa-c03/index.json`Exam - Project Instructions

## 🎯 Project Vision
Create a free, efficient, and scalable exam preparation platform that serves questions via GitHub repository, eliminating the need for expensive hosting while maintaining high performance.

## 🚀 AWS SAA-C03 Automation System - ACTIVE
**Status**: ✅ Deployed and Operational
**Daily Sync**: 6:00 AM UTC from https://github.com/Iamrushabhshahh/AWS-Certified-Solutions-Architect-Associate-SAA-C03-Exam-Dump-With-Solution.git
**CDN Access**: https://cdn.jsdelivr.net/gh/Shivaprasadr/TestBeforeExam@main/data/subjects/cloud-computing/aws/

### Live Endpoints
- Master Index: `index.json`
- Storage Questions: `storage/storage-questions.json`
- Analytics Questions: `analytics/analytics-questions.json`  
- Security Questions: `security/security-questions.json`

## 🏗️ Architecture Philosophy
- **Free & Efficient**: Leverage free services (GitHub, Netlify, Vercel, jsDelivr CDN)
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

## � CRITICAL: File Management Rules

### **NEVER CREATE NEW DOCUMENTATION FILES**
- **Only update existing files**: README.md, INSTRUCTIONS.md, PROMPTS.md
- **No additional .md files**: No context files, config files, or AI-specific files
- **One source of truth**: Each topic has ONE location in these three files
- **Update, don't duplicate**: Always enhance existing content instead of creating new files

### **File Responsibilities**
- **README.md**: Project overview, getting started, architecture, technical specs
- **INSTRUCTIONS.md**: Development guidelines, project evolution, detailed workflows
- **PROMPTS.md**: AI development patterns, code generation prompts
- **CONTRIBUTING.md**: Contribution guidelines only (keep minimal)

### **Folder Structure Rules**
- **Root level**: Only essential files (README, INSTRUCTIONS, PROMPTS, CONTRIBUTING, LICENSE)
- **`.github/`**: GitHub templates only
- **`data/`**: Question content and schemas
- **`apps/`**: Application source code
- **`tools/`**: Development utilities
- **NO `docs/` folder**: All documentation in root-level files

## �🔄 Self-Evolution Guidelines

### When to Update These Files
- [ ] New major features are added → Update INSTRUCTIONS.md
- [ ] Architecture changes occur → Update README.md architecture section
- [ ] New development patterns → Update PROMPTS.md
- [ ] Community feedback → Update relevant sections in existing files
- [ ] Performance optimizations → Update README.md performance section

### Evolution Triggers
1. **Repository Growth**: Update INSTRUCTIONS.md structure section
2. **Feature Additions**: Update README.md features and INSTRUCTIONS.md workflows
3. **Community Feedback**: Update CONTRIBUTING.md and relevant instruction sections
4. **Technology Updates**: Update README.md tech stack and INSTRUCTIONS.md guidelines
5. **Performance Insights**: Update README.md performance targets

## 🛠️ Development Workflow

### 1. Content Management
- Questions stored in JSON format following strict schema
- Categorized by subject, difficulty, and exam type
- Version controlled for change tracking
- Automated validation on commits
- Content organized in `data/subjects/{subject}/{topic}.json`

### 2. Application Development
- Progressive Web App (PWA) for web using React + TypeScript
- React Native for mobile (using Expo)
- Shared TypeScript codebase in `apps/shared/`
- Component-driven development with Tailwind CSS
- Vite for fast builds and hot reloading

### 3. Deployment Strategy
- **Web App**: Netlify/Vercel (free tier) with automatic deployments
- **Mobile App**: Expo Application Services for app store distribution
- **API**: GitHub raw content API + jsDelivr CDN
- **Content Delivery**: jsDelivr for global fast content access

### 4. Development Environment Setup
```bash
# Prerequisites: Node.js 16+, Git
git clone https://github.com/Shivaprasadr/TestBeforeExam.git
cd TestBeforeExam
npm install
npm run dev    # Start development server
npm run test   # Run test suite
npm run build  # Production build
```

### 5. Code Quality Standards
- **TypeScript**: Strict mode enabled, proper typing required
- **Testing**: Jest + Testing Library, >80% coverage target
- **Linting**: ESLint + Prettier for consistent code style
- **Accessibility**: WCAG 2.1 AA compliance mandatory
- **Performance**: Bundle size monitoring, lazy loading patterns

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