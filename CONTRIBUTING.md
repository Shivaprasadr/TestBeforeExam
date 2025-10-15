# 🤝 Contributing to TestBeforeExam

Thank you for your interest in contributing to TestBeforeExam! This document provides guidelines and information for contributing to our free, open-source exam preparation platform.

## 🌟 Ways to Contribute

### 📚 Content Contribution
- Add exam questions and explanations
- Review and validate existing content
- Create subject-specific question sets
- Improve question quality and clarity

### 💻 Code Contribution
- Develop new features
- Fix bugs and issues
- Improve performance
- Enhance user experience

### 📝 Documentation
- Improve existing documentation
- Create tutorials and guides
- Translate content
- Write API documentation

### 🎨 Design & UX
- Design user interfaces
- Create graphics and illustrations
- Improve accessibility
- Conduct user experience research

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- Git
- Code editor (VS Code recommended)
- Basic knowledge of TypeScript/JavaScript

### Development Setup
```bash
# 1. Fork the repository on GitHub
# 2. Clone your fork
git clone https://github.com/YOUR_USERNAME/TestBeforeExam.git
cd TestBeforeExam

# 3. Add upstream remote
git remote add upstream https://github.com/Shivaprasadr/TestBeforeExam.git

# 4. Install dependencies
npm install

# 5. Create a feature branch
git checkout -b feature/your-feature-name

# 6. Start development server
npm run dev
```

## 📋 Contribution Process

### 1. Planning Your Contribution
- Check existing [issues](https://github.com/Shivaprasadr/TestBeforeExam/issues)
- Join [discussions](https://github.com/Shivaprasadr/TestBeforeExam/discussions)
- Create an issue for new features or significant changes
- Get feedback before starting major work

### 2. Making Changes
- Follow our coding standards
- Write clear, descriptive commit messages
- Include tests for new functionality
- Update documentation as needed
- Ensure accessibility compliance

### 3. Submitting Changes
- Push your changes to your fork
- Create a pull request with clear description
- Link related issues
- Wait for review and address feedback
- Celebrate when merged! 🎉

## 📊 Content Contribution Guidelines

### Question Format
All questions must follow our standard schema:

```json
{
  "id": "unique-question-id",
  "subject": "mathematics",
  "topic": "algebra",
  "subtopic": "linear-equations",
  "difficulty": "medium",
  "examTypes": ["SAT", "GRE"],
  "question": "Solve for x: 2x + 5 = 13",
  "questionType": "multiple-choice",
  "options": [
    "x = 4",
    "x = 9",
    "x = 6",
    "x = 8"
  ],
  "correctAnswer": 0,
  "explanation": "Subtract 5 from both sides: 2x = 8. Divide by 2: x = 4.",
  "tags": ["linear-equations", "basic-algebra"],
  "timeEstimate": 60,
  "difficulty_justification": "Requires basic algebraic manipulation",
  "metadata": {
    "createdAt": "2025-10-15T00:00:00Z",
    "contributor": "your-github-username",
    "reviewedBy": null,
    "verified": false,
    "source": "original",
    "references": []
  }
}
```

### Content Quality Standards
1. **Accuracy**: All answers must be correct and verified
2. **Clarity**: Questions should be clear and unambiguous
3. **Appropriate Difficulty**: Match the specified difficulty level
4. **Educational Value**: Include helpful explanations
5. **Original Content**: Avoid copyright infringement
6. **Inclusive Language**: Use accessible, inclusive language

### File Organization
```
data/
├── subjects/
│   ├── mathematics/
│   │   ├── algebra/
│   │   │   ├── basic-algebra.json
│   │   │   └── advanced-algebra.json
│   │   └── geometry/
│   └── science/
│       ├── physics/
│       └── chemistry/
└── schemas/
    └── question-schema.json
```

## 💻 Code Contribution Guidelines

### Coding Standards
- Use TypeScript for all new code
- Follow existing code style and conventions
- Use meaningful variable and function names
- Write self-documenting code with comments
- Follow SOLID principles

### File Structure
```
apps/
├── web/                    # Web application
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Page components
│   │   ├── hooks/          # Custom React hooks
│   │   ├── utils/          # Utility functions
│   │   ├── services/       # API services
│   │   ├── types/          # TypeScript type definitions
│   │   └── styles/         # Styling files
│   └── public/             # Static assets
├── mobile/                 # Mobile application
└── shared/                 # Shared code between platforms
    ├── types/              # Shared TypeScript types
    ├── utils/              # Shared utility functions
    └── services/           # Shared API services
```

### Testing Requirements
- Write unit tests for new functionality
- Ensure existing tests pass
- Aim for >80% code coverage
- Include integration tests for complex features

```bash
# Run tests
npm run test

# Run tests with coverage
npm run test:coverage

# Run E2E tests
npm run test:e2e
```

### Performance Guidelines
- Optimize bundle size
- Use lazy loading for components
- Implement proper caching strategies
- Consider mobile performance
- Test on low-end devices

## 🎯 Specific Contribution Areas

### High Priority Needs
1. **Subject Matter Experts** for content creation
2. **Frontend Developers** for React/TypeScript development
3. **Mobile Developers** for React Native development
4. **UX Designers** for user experience improvements
5. **DevOps Engineers** for CI/CD and deployment

### Current Focus Areas
- Basic mathematics questions (algebra, geometry)
- Web application core features
- Mobile app development
- Performance optimization
- Accessibility improvements

## 🔍 Review Process

### Pull Request Review
All contributions go through our review process:

1. **Automated Checks**
   - Code style and linting
   - Test suite execution
   - Build verification
   - Content validation

2. **Human Review**
   - Code quality assessment
   - Content accuracy verification
   - User experience evaluation
   - Security considerations

3. **Community Feedback**
   - Open discussion on changes
   - Feedback from subject matter experts
   - User testing when applicable

### Review Criteria
- Functionality works as expected
- Code follows project standards
- Tests are comprehensive
- Documentation is updated
- No breaking changes (unless approved)
- Accessibility compliance
- Performance impact acceptable

## 🏆 Recognition System

### Contributor Levels
- **Student**: First-time contributors
- **Scholar**: Regular contributors with quality contributions
- **Expert**: Subject matter experts with significant contributions
- **Maintainer**: Core team members with repository access

### Recognition Methods
- GitHub contributor acknowledgments
- Contributor profiles in documentation
- Special badges and achievements
- Community spotlight features
- Annual contributor awards

## 📖 Resources

### Documentation
- [Project Instructions](INSTRUCTIONS.md)
- [Development Prompts](PROMPTS.md)
- [API Documentation](docs/API.md) *(Coming Soon)*
- [Deployment Guide](docs/DEPLOYMENT.md) *(Coming Soon)*

### Tools and Technologies
- [React Documentation](https://reactjs.org/docs/)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/)
- [React Native Documentation](https://reactnative.dev/docs/getting-started)
- [Testing Library](https://testing-library.com/docs/)

### Community Resources
- [GitHub Discussions](https://github.com/Shivaprasadr/TestBeforeExam/discussions)
- [Discord Server](https://discord.gg/testbeforeexam) *(Coming Soon)*
- [Contributors Guide](https://docs.github.com/en/get-started/quickstart/contributing-to-projects)

## ❓ Getting Help

### For Questions
1. Check existing documentation
2. Search GitHub issues and discussions
3. Ask in GitHub Discussions
4. Contact maintainers directly

### For Issues
1. Check if issue already exists
2. Provide detailed reproduction steps
3. Include system information
4. Add relevant labels and assignees

## 📜 Code of Conduct

### Our Standards
- Be respectful and inclusive
- Welcome newcomers and help them learn
- Provide constructive feedback
- Focus on what's best for the community
- Show empathy towards other community members

### Unacceptable Behavior
- Harassment or discrimination
- Trolling or insulting comments
- Personal or political attacks
- Public or private harassment
- Publishing others' private information
- Other conduct inappropriate in a professional setting

### Enforcement
Community leaders will enforce these standards fairly and consistently. Violations may result in temporary or permanent bans from the community.

## 🎉 Thank You!

Your contributions make TestBeforeExam better for millions of students worldwide. Every contribution, no matter how small, makes a difference in democratizing education.

### Quick Checklist Before Submitting
- [ ] Read and understood contribution guidelines
- [ ] Followed coding standards and conventions
- [ ] Added/updated tests as needed
- [ ] Updated documentation if required
- [ ] Tested changes thoroughly
- [ ] Created clear, descriptive commit messages
- [ ] Linked relevant issues in pull request

---

**Happy Contributing! 🚀**

*For questions or clarifications, please create an issue or start a discussion.*