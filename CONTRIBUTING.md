# Contributing to Repository Naming Convention

Thank you for your interest in improving this repository naming standard! We welcome contributions from developers of all backgrounds and experience levels.

## 🌟 Ways to Contribute

There are many ways you can help make this convention better:

- **Suggest new components** (prefixes, types, languages/frameworks, tags)
- **Share real-world examples** of the convention in use
- **Report issues** with the current convention or documentation
- **Improve documentation** (fix typos, clarify explanations, add examples)
- **Translate documentation** to other languages
- **Build tools** that implement or validate this standard
- **Share feedback** on your experience using the convention

## 🚀 Quick Start

### Suggesting New Components

Before suggesting a new component, please:

1. **Search existing issues** to see if it's already been proposed
2. **Check the current convention** to ensure it's not already included
3. **Consider if it's widely applicable** across different projects and teams

### Types of Suggestions

#### 1️⃣ New Prefix

**When to suggest a new prefix:**
- It represents a common project categorization
- It's distinct from existing prefixes
- It would be useful across multiple domains/industries

**Example suggestion:**
```markdown
**Prefix**: `client`
**Description**: Client/customer-specific customization
**Use Case**: Agencies or consultancies maintaining client-specific forks
**Examples**: 
- client-web-acme-portal
- client-mobile-globex-app
```

#### 2️⃣ New Type

**When to suggest a new type:**
- It represents a distinct project category not covered by existing types
- Multiple projects would benefit from this classification
- It's commonly understood in software development

**Example suggestion:**
```markdown
**Type**: `extension`
**Description**: Browser extension or IDE extension
**Use Case**: Tools that extend existing applications
**Examples**:
- extension-chrome-productivity-tracker
- extension-vscode-theme-switcher
**Why not existing types?**: "plugin" is too generic; extensions are a specific category
```

#### 3️⃣ New Language/Framework

**When to suggest a new language/framework:**
- It's actively maintained with a substantial user base
- It's distinct enough to warrant its own tag (not a subset of another)
- Developers would search for projects using this technology

**Example suggestion:**
```markdown
**Language/Framework**: `elixir`
**Description**: Elixir programming language
**Popularity**: ~6k GitHub stars, growing adoption in real-time systems
**Examples**:
- api-elixir-websocket-service
- web-elixir-phoenix-dashboard
**Related frameworks to consider**: phoenix (framework)
```

#### 4️⃣ New Tag

**When to suggest a new tag:**
- It indicates a useful project status not covered by existing tags
- It helps developers quickly understand project maturity/state
- It's commonly used in software development

**Example suggestion:**
```markdown
**Tag**: `maintenance`
**Description**: Project in maintenance mode (bug fixes only, no new features)
**Use Case**: Projects that are stable but not actively developed
**Examples**:
- lib-python-legacy-parser-maintenance
- api-node-auth-v1-maintenance
```

## 📋 Contribution Guidelines

### General Principles

When contributing, please keep these principles in mind:

1. **Clarity over cleverness** - Names should be immediately understandable
2. **Consistency** - New additions should fit the existing pattern
3. **Brevity** - Avoid overly long or complex terms
4. **Universal understanding** - Use widely recognized terms, not jargon
5. **Language agnostic** - The convention should work for any programming language

### Quality Standards

#### For New Components

All suggestions should include:

- **Clear definition** - What does this component represent?
- **Use cases** - When would developers use this?
- **Examples** - At least 3 realistic repository names
- **Justification** - Why is this needed? What gap does it fill?
- **Alternatives considered** - Could existing components work?

#### For Documentation Improvements

- Fix typos and grammatical errors
- Clarify confusing explanations
- Add helpful examples
- Improve formatting and readability
- Ensure consistency in terminology

#### For Code Contributions

- Follow existing code style
- Test your changes thoroughly
- Update documentation to reflect changes
- Keep commits focused and atomic

## 🛠️ How to Submit

### Option 1: GitHub Issues (Recommended for Suggestions)

1. Go to the [Issues tab](https://github.com/your-username/docs-repository-naming-convention/issues)
2. Click **New Issue**
3. Choose the appropriate template:
   - 💡 Suggest New Component
   - 🐛 Report Issue
   - 📚 Documentation Improvement
   - 🔧 Tool/Integration Idea
4. Fill out the template with as much detail as possible
5. Submit and wait for community feedback

### Option 2: Pull Requests (For Direct Changes)

1. **Fork the repository**
   ```bash
   # Click "Fork" button on GitHub, then:
   git clone https://github.com/YOUR-USERNAME/docs-repository-naming-convention.git
   cd docs-repository-naming-convention
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/add-elixir-framework
   ```

3. **Make your changes**
   - Update `README.md` with new component
   - Update `index.html` generator if applicable
   - Add examples to documentation

4. **Test your changes**
   - Ensure all links work
   - Verify the generator still functions (if modified)
   - Check that examples are valid

5. **Commit with a clear message**
   ```bash
   git add .
   git commit -m "Add Elixir to language/framework list with examples"
   ```

6. **Push and create pull request**
   ```bash
   git push origin feature/add-elixir-framework
   ```
   Then go to GitHub and click "Create Pull Request"

7. **Describe your changes**
   - Explain what you've added/changed
   - Provide context and reasoning
   - Link to any related issues

### Option 3: GitHub Discussions (For Open-Ended Ideas)

For brainstorming or asking questions:

1. Go to [Discussions](https://github.com/your-username/docs-repository-naming-convention/discussions)
2. Start a new discussion in the appropriate category:
   - **Ideas** - Brainstorm new features or changes
   - **Q&A** - Ask questions about the convention
   - **Show and Tell** - Share how you're using the convention
   - **General** - Other topics

## 📝 Issue Templates

We provide several issue templates to make contributing easier:

### 💡 Suggest New Component

Use this when proposing a new prefix, type, language/framework, or tag.

**Required information:**
- Component type (prefix/type/language/tag)
- Name and description
- Use cases and examples
- Justification

### 🐛 Report Issue

Use this for problems with the convention or documentation.

**Required information:**
- What's the problem?
- Where did you encounter it?
- What did you expect?
- Suggested solution (optional)

### 📚 Documentation Improvement

Use this for suggesting documentation changes.

**Required information:**
- Which section needs improvement?
- What's unclear or missing?
- Suggested changes

### 🔧 Tool/Integration Idea

Use this for proposing tools or integrations.

**Required information:**
- What tool/integration?
- What problem does it solve?
- Technical approach (if known)

## 🎯 What We're Looking For

### High Priority

These contributions are especially valuable:

- **Popular languages/frameworks** that are missing (check npm, PyPI, GitHub trends)
- **Real-world use cases** and success stories
- **Translations** of the main documentation
- **Validation tools** (CLI, GitHub Actions, browser extensions)
- **Examples from different industries** (fintech, gaming, IoT, etc.)

### Needs Discussion

These need careful consideration before adding:

- **Very niche technologies** (small user base)
- **Changes to core format** (the `{prefix-}type-{language-}project{-tag}` structure)
- **Controversial naming choices** (terms with multiple meanings)
- **Regional-specific terms** (may not translate well)

### Probably Won't Accept

To keep the convention focused, we likely won't accept:

- **Company-specific terms** (internal jargon)
- **Overly granular categories** (too specific)
- **Redundant components** (overlaps with existing ones)
- **Deprecated technologies** (no longer maintained)
- **Joke suggestions** (keep it professional)

## ✅ Review Process

1. **Submission** - You submit an issue or pull request
2. **Initial Review** - Maintainers review within 7 days
3. **Community Feedback** - Open for community input (14 days)
4. **Discussion** - Questions, refinements, alternatives
5. **Decision** - Accepted, needs changes, or declined (with explanation)
6. **Merge** - If accepted, merged and added to CHANGELOG

We aim to respond to all contributions within **one week**. Complex proposals may take longer to evaluate.

## 🏆 Recognition

All contributors are recognized in our README! Significant contributions also get:

- Listed in [CONTRIBUTORS.md](CONTRIBUTORS.md)
- Mentioned in release notes
- Special badge on your GitHub profile (if you want one)
- Eternal gratitude from the community 🙏

## 💬 Communication

- **Questions?** Open a [Discussion](https://github.com/your-username/docs-repository-naming-convention/discussions)
- **Quick chat?** Join our [Discord](https://discord.gg/your-invite) (coming soon)
- **Found a bug?** Open an [Issue](https://github.com/your-username/docs-repository-naming-convention/issues)
- **Want to help?** Check [Good First Issues](https://github.com/your-username/docs-repository-naming-convention/labels/good%20first%20issue)

## 📜 Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to uphold this code. Please report unacceptable behavior to [conduct@your-email.com].

**TL;DR**: Be respectful, constructive, and professional. We're all here to improve software development practices together.

## 🙋 Need Help?

- **First time contributing?** Check out [First Contributions](https://github.com/firstcontributions/first-contributions)
- **Stuck on something?** Open a discussion with the "help wanted" tag
- **Not sure if your idea fits?** Ask in Discussions before opening an issue

## 📚 Additional Resources

- [How to Write a Good Issue](https://github.com/necolas/issue-guidelines)
- [How to Write a Good Pull Request](https://github.blog/2015-01-21-how-to-write-the-perfect-pull-request/)
- [Semantic Commit Messages](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)

---

**Thank you for helping make repository naming better for everyone!** 🎉

Every contribution, no matter how small, helps improve the developer experience for thousands of people.