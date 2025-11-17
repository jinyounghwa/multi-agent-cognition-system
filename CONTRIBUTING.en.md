# Contributing to Multi-Agent Cognition System

[한국어](CONTRIBUTING.ko.md) | [日本語](CONTRIBUTING.ja.md)

---

Thank you for your interest in contributing to the Multi-Agent Cognition System (MCS)! This project is a community-driven thinking framework, and your contributions help make it better for everyone.

---

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Getting Started](#getting-started)
- [Pull Request Process](#pull-request-process)
- [Style Guidelines](#style-guidelines)
- [Commit Message Guidelines](#commit-message-guidelines)
- [Review Process](#review-process)
- [Questions?](#questions)

---

## Code of Conduct

### Our Pledge

We are committed to making participation in this project a harassment-free experience for everyone, regardless of level of experience, gender, gender identity and expression, sexual orientation, disability, personal appearance, body size, race, ethnicity, age, religion, or nationality.

### Our Standards

**Examples of behavior that contributes to a positive environment:**
- ✅ Being respectful of differing viewpoints and experiences
- ✅ Gracefully accepting constructive criticism
- ✅ Focusing on what is best for the community
- ✅ Showing empathy towards other community members

**Examples of unacceptable behavior:**
- ❌ Trolling, insulting/derogatory comments, and personal attacks
- ❌ Public or private harassment
- ❌ Publishing others' private information without permission
- ❌ Other conduct which could reasonably be considered inappropriate

---

## How Can I Contribute?

### 🧠 Methodology Improvements

**What:** Suggest improvements to the 6-perspective framework or MCS methodology

**Examples:**
- Proposing a new perspective or refining existing ones
- Suggesting improvements to the reflection process
- Sharing research that supports or challenges the methodology

**How to contribute:**
1. Open an issue with the `methodology` label
2. Describe the improvement and rationale
3. Provide examples or research supporting your suggestion
4. Discuss with the community before implementing

---

### 📝 Documentation Enhancements

**What:** Improve clarity, fix errors, or add missing documentation

**Examples:**
- Fixing typos, grammar, or formatting
- Clarifying confusing sections
- Adding diagrams or visualizations
- Expanding explanations with examples

**How to contribute:**
1. Make your changes in the appropriate `.md` file
2. Submit a pull request with clear description
3. Reference any related issues

**Documentation structure:**
```
docs/
├── en/  (English documentation)
├── ko/  (Korean documentation)
└── ja/  (Japanese documentation)
```

---

### 🌍 Translations

**What:** Translate documentation to new languages or improve existing translations

**Current languages:**
- ✅ English
- ✅ Korean (한국어)
- ✅ Japanese (日本語)

**Adding a new language:**
1. Create language directory: `docs/[language-code]/`
2. Translate core documents (start with `01-core-concepts.md`)
3. Update navigation in `docs/README.md`
4. Submit pull request

**Translation guidelines:**
- Maintain the same structure as English version
- Use culturally appropriate examples when needed
- Keep technical terms consistent
- Link between language versions for easy navigation

---

### 📋 Examples and Templates

**What:** Share your MCS practice examples or create new templates

**Examples to contribute:**
- Daily reflection examples showing real MCS application
- Weekly/monthly integration examples
- Project analysis examples
- Business idea generation examples

**How to contribute:**
1. Use existing template structure
2. Ensure example is complete and high-quality
3. Add to appropriate directory under `examples/`
4. Update `examples/README.md` with your new example

**Quality standards for examples:**
- All 6 perspectives should be thoughtfully analyzed
- Include specific, actionable insights
- Show connections between perspectives
- Demonstrate business/learning/project applications

---

### 🛠️ Tools and Automation

**What:** Create tools to enhance the MCS practice

**Examples:**
- Scripts to analyze daily reflections
- Pattern recognition tools
- Automation for template generation
- Web-based reflection interfaces

**How to contribute:**
1. Create tool in `tools/` directory
2. Include clear documentation on usage
3. Add dependencies to requirements (if applicable)
4. Provide example usage

**Tool guidelines:**
- Keep tools optional (MCS should work without them)
- Focus on reducing friction, not replacing thinking
- Document clearly for non-technical users
- Include tests if applicable

---

### 🎨 Design Improvements

**What:** Improve visual design, diagrams, or user experience

**Examples:**
- Creating diagrams explaining MCS concepts
- Improving README layout
- Designing visual templates
- Creating infographics

**How to contribute:**
1. Discuss design ideas in an issue first
2. Use widely compatible formats (PNG, SVG for images)
3. Ensure accessibility (color contrast, alt text)
4. Submit pull request with design files

---

## Getting Started

### Prerequisites

- Git installed on your computer
- GitHub account
- Text editor (VS Code, Sublime, etc.)
- Basic understanding of Markdown

### Setup

1. **Fork the repository**
   ```bash
   # Click "Fork" button on GitHub
   ```

2. **Clone your fork**
   ```bash
   git clone https://github.com/jinyounghwa/multi-agent-cognition-system.git
   cd multi-agent-cognition-system
   ```

3. **Create a branch**
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/issue-description
   ```

4. **Make your changes**
   - Edit files as needed
   - Test your changes (read through, check links, etc.)

5. **Commit your changes**
   ```bash
   git add .
   git commit -m "Brief description of changes"
   ```

6. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

7. **Create Pull Request**
   - Go to original repository on GitHub
   - Click "New Pull Request"
   - Select your branch
   - Fill in PR template

---

## Pull Request Process

### Before Submitting

- [ ] Read the relevant documentation
- [ ] Test your changes thoroughly
- [ ] Check for typos and formatting
- [ ] Update navigation/links if needed
- [ ] Follow style guidelines
- [ ] Write clear commit messages

### PR Description Template

```markdown
## Description
[Describe what this PR does]

## Type of Change
- [ ] Documentation improvement
- [ ] New example
- [ ] Translation
- [ ] Tool/automation
- [ ] Methodology improvement
- [ ] Bug fix

## Related Issues
Fixes #[issue number]

## Checklist
- [ ] I have tested my changes
- [ ] I have updated relevant documentation
- [ ] I have followed the style guidelines
- [ ] My changes don't break existing functionality
```

### Review Process

1. **Automated checks** (if any) must pass
2. **Maintainer review** - usually within 3-5 days
3. **Community feedback** - open for discussion
4. **Requested changes** - address any feedback
5. **Approval & merge** - once approved by maintainer

---

## Style Guidelines

### Markdown Formatting

**Headers:**
```markdown
# Main Title (H1) - Only one per document
## Section (H2)
### Subsection (H3)
```

**Lists:**
- Use `-` for unordered lists
- Use `1.` for ordered lists
- Indent nested lists with 2 spaces

**Code blocks:**
```markdown
Use triple backticks with language identifier:
​```python
def example():
    pass
​```
```

**Links:**
```markdown
[Link text](relative/path/to/file.md)
[External link](https://example.com)
```

**Emphasis:**
```markdown
**Bold** for strong emphasis
*Italic* for light emphasis
`code` for inline code/technical terms
```

### Writing Style

**Be Clear:**
- Use simple, direct language
- Avoid jargon unless necessary
- Define technical terms when first used

**Be Concise:**
- Get to the point quickly
- Use examples to illustrate concepts
- Break up long paragraphs

**Be Consistent:**
- Follow existing document structure
- Use same terminology throughout
- Match the tone of existing content

**Be Inclusive:**
- Use gender-neutral language
- Consider different cultural contexts
- Provide examples from diverse backgrounds

---

## Commit Message Guidelines

### Format

```
<type>(<scope>): <subject>

<body>

<footer>
```

### Types

- `docs`: Documentation changes
- `feat`: New feature or example
- `fix`: Bug fix or correction
- `style`: Formatting, missing semicolons, etc.
- `refactor`: Code/content restructuring
- `test`: Adding tests
- `chore`: Maintenance tasks

### Examples

```bash
docs(core-concepts): clarify perspective rotation principle

Added more detailed explanation of how to rotate perspectives
daily, with concrete examples.

Fixes #123
```

```bash
feat(examples): add React Hooks learning example

Created comprehensive example showing MCS application to
learning React Hooks, including all 6 perspectives and
generated business insights.
```

```bash
fix(navigation): correct broken links in examples README

Updated Quick Navigation to only show existing files,
added "Coming Soon" section for planned examples.
```

### Best Practices

- Use present tense ("add" not "added")
- Use imperative mood ("move" not "moves")
- First line limited to 72 characters
- Reference issues and pull requests when relevant
- Explain *what* and *why*, not *how*

---

## Review Process

### What We Look For

**Quality:**
- Is the content accurate and helpful?
- Does it follow the style guidelines?
- Is it well-organized and clear?

**Completeness:**
- Is documentation updated?
- Are examples thorough?
- Are links working?

**Consistency:**
- Does it match existing content style?
- Is terminology consistent?
- Does it fit the overall framework?

### Timeline

- **Initial review:** Within 3-5 days
- **Follow-up:** Within 2-3 days of updates
- **Merge:** Once approved and all checks pass

### Feedback

We aim to provide:
- Constructive, specific feedback
- Clear explanations for requested changes
- Appreciation for your contribution

Please:
- Be open to feedback
- Ask questions if unclear
- Be patient with the review process

---

## Questions?

### Before Opening an Issue

- Check existing issues and discussions
- Read relevant documentation
- Search for similar questions

### Where to Ask

**For questions about:**
- **Using MCS:** Open a Discussion
- **Bug reports:** Open an Issue with `bug` label
- **Feature requests:** Open an Issue with `enhancement` label
- **Methodology questions:** Open a Discussion
- **General questions:** Open a Discussion

### Issue Templates

When opening an issue, please:
1. Use descriptive title
2. Provide context and details
3. Include examples when relevant
4. Be respectful and constructive

---

## Recognition

Contributors will be:
- Listed in project acknowledgments
- Mentioned in release notes (if applicable)
- Credited in the contributed content

---

## Thank You!

Every contribution, no matter how small, helps make MCS better for the community. We appreciate your time and effort!

**Some ideas for first contributions:**
- Fix a typo in documentation
- Improve clarity of an existing section
- Add an example from your own MCS practice
- Translate a document to your language
- Suggest a methodology improvement

**Questions?** Don't hesitate to ask in Discussions or Issues!

---

**Happy contributing! 🎉**

---

[Back to Main README](README.md) | [View in Korean](CONTRIBUTING.ko.md) | [View in Japanese](CONTRIBUTING.ja.md)
