# 🤝 Contributing to TestBeforeExam

Thank you for contributing to our free exam preparation platform!

## 🌟 Ways to Contribute

### 📚 Content: Add questions, explanations, and subject areas
### 💻 Code: Develop features, fix bugs, improve performance  
### 🎨 Design: Create UI/UX improvements and graphics
### 📝 Documentation: Update README.md, INSTRUCTIONS.md, or PROMPTS.md only

## 🚀 Quick Start

```bash
# Fork repository, then:
git clone https://github.com/YOUR_USERNAME/TestBeforeExam.git
cd TestBeforeExam
npm install
npm run dev
```

## 📋 Contribution Process

1. **Plan**: Check issues, create new issue if needed
2. **Code**: Follow TypeScript standards, include tests
3. **Test**: Ensure accessibility and performance
4. **Submit**: Create PR with clear description
5. **Iterate**: Address review feedback

## 📊 Content Guidelines

### Question Format (see README.md for full schema)
```json
{
  "id": "math-algebra-001",
  "subject": "mathematics",
  "topic": "algebra",
  "difficulty": "beginner",
  "question": "Solve: 2x + 5 = 13",
  "options": ["x = 4", "x = 9", "x = 6", "x = 8"],
  "correctAnswer": 0,
  "explanation": "Subtract 5: 2x = 8. Divide by 2: x = 4"
}
```

### Quality Standards
- ✅ Accurate answers with clear explanations
- ✅ Appropriate difficulty levels
- ✅ Original content or properly attributed
- ✅ Inclusive, accessible language

## 💻 Code Standards

- **TypeScript**: Strict mode, proper typing required
- **Testing**: Jest + Testing Library, >80% coverage
- **Performance**: < 3s load time, mobile optimized
- **Accessibility**: WCAG 2.1 AA compliance

## 🔍 Review Process

All PRs reviewed for:
- Code quality and standards
- Test coverage
- Performance impact
- Accessibility compliance

## 📖 Resources

- Check INSTRUCTIONS.md for detailed guidelines
- Use PROMPTS.md for development patterns
- Follow GitHub issue templates

---

**Questions?** Create an issue or discussion thread.