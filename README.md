# Repository Naming Convention

A standardized approach to naming GitHub repositories for improved organization, discoverability, and consistency across projects.

[![Standard](https://img.shields.io/badge/standard-v1.0-blue.svg)](https://github.com/reslava/docs-repository-naming-convention)
[![Naming Convention](https://img.shields.io/badge/naming-compliant-green.svg)](https://github.com/reslava/docs-repository-naming-convention)
[![Generator](https://img.shields.io/badge/🚀-Try_the_Generator-success.svg)](https://your-username.github.io/docs-repository-naming-convention/)

## 🚀 Try the Interactive Generator

**Don't want to read the whole guide?** Use our web-based name generator:

👉 **[Launch the Generator](https://reslava.github.io/docs-repository-naming-convention/)** 👈

Simply fill in the dropdowns, and get a perfectly formatted repository name instantly!

---

## 📌 Naming Format

```
{prefix-}type-{language/framework-}project{-tag}
```

**Note:** Elements in `{}` are optional

---

## Convention Components

### Prefix
| Prefix | Description | Use Case |
|--------|-------------|----------|
| `study` | Learning or educational projects | Personal learning, courses, tutorials |
| `fork` | Forked repository with modifications | Modified third-party code |
| `template` | Reusable project template | Boilerplates, starter kits |
| `poc` | Proof of concept | Experimental validation |
| `demo` | Demonstration project | Showcases, examples |
| `archived` | Historical/reference project | Old versions, legacy code |
| `experimental` | Experimental or research project | R&D, prototypes |

### Type
| Type | Description |
|------|-------------|
| `course` | Course materials or coursework |
| `tutorial` | Tutorial or guide implementation |
| `docs` | Documentation repository |
| `api` | API service or endpoint |
| `lib` | Library or package |
| `cli` | Command-line interface tool |
| `plugin` | Plugin or extension |
| `theme` | Theme or styling package |
| `bot` | Bot application (Discord, Telegram, etc.) |
| `game` | Game development project |
| `mobile` | Mobile application |
| `desktop` | Desktop application |
| `web` | Web application |
| `saas` | Software as a Service application |
| `microservices` | Microservices architecture |
| `script` | Utility or automation scripts |
| `config` | Configuration files repository |
| `infra` | Infrastructure as Code |

### Language/Framework
| Language/Framework | Usage |
|-------------------|-------|
| `aspnet` | ASP.NET projects |
| `net` | .NET projects (non-ASP.NET) |
| `csharp` | C# projects |
| `unity` | Unity game engine projects |
| `python` | Python projects |
| `django` | Django framework |
| `fastapi` | FastAPI framework |
| `flask` | Flask framework |
| `php` | PHP projects |
| `laravel` | Laravel framework |
| `node` | Node.js projects |
| `express` | Express.js framework |
| `react` | React applications |
| `nextjs` | Next.js applications |
| `vue` | Vue.js applications |
| `nuxt` | Nuxt.js applications |
| `angular` | Angular applications |
| `svelte` | Svelte applications |
| `javascript` | JavaScript projects |
| `typescript` | TypeScript projects |
| `go` | Go/Golang projects |
| `rust` | Rust projects |
| `java` | Java projects |
| `spring` | Spring framework |
| `kotlin` | Kotlin projects |
| `swift` | Swift projects |
| `flutter` | Flutter framework |
| `dart` | Dart projects |
| `ruby` | Ruby projects |
| `rails` | Ruby on Rails |
| `elixir` | Elixir projects |
| `shell` | Shell scripts |
| `terraform` | Terraform IaC |
| `ansible` | Ansible playbooks |

### Tag
| Tag | Description |
|-----|-------------|
| `abandoned` | Discontinued project, no longer maintained |
| `deprecated` | Replaced by newer version/approach |
| `wip` | Work in progress, not production-ready |
| `beta` | Beta version, testing phase |
| `legacy` | Old version kept for reference |
| `archived` | Completed/historical, read-only |

---

## 🎨 Quick Start: Use the Generator

The fastest way to create compliant repository names is with our **interactive web tool**:

### [🚀 Open the Name Generator](https://your-username.github.io/docs-repository-naming-convention/)

**Features:**
- ✅ Dropdown menus with all components (sorted alphabetically)
- ✅ Real-time name generation as you type
- ✅ Validation with helpful warnings
- ✅ One-click copy to clipboard
- ✅ Clickable examples to learn the pattern
- ✅ Works on mobile and desktop

**No installation needed** - just open in your browser and start creating names!

---

## Best Practices

| Aspect | Recommendation |
|--------|----------------|
| **Case and Separators** | Use **lowercase** and **hyphenated** names for readability and consistency |
| **Descriptive Keywords** | Include descriptors like "docs", "lib", "api", "cli" |
| **Avoid Special Characters** | Do not use underscores, spaces, or version formats |
| **Avoid Version Numbers** | Use tags or release diffs for version management instead |
| **Stability Over Time** | Avoid organizational or department names that may change |
| **Consistency Across Repos** | Follow a uniform naming pattern for ease of categorization |
| **Descriptive Yet Concise** | Aim for **3-5 words** to balance clarity and brevity* |
| **Language Specificity** | Include language/framework only when it adds value |
| **Universal Understanding** | Use widely recognized terms over internal jargon |

**Note:** When using prefix or tag, exceeding 5 words is acceptable.

---

## Examples

### Good Examples ✅

```
study-course-react-todo-app
docs-api-reference
aspnet-api-user-service
lib-python-data-validation
cli-go-deployment-tool
web-nextjs-portfolio
mobile-flutter-expense-tracker
bot-discord-moderation
plugin-vscode-theme-switcher
poc-rust-blockchain
template-django-starter
fork-react-admin-dashboard
microservices-node-auth-service
infra-terraform-aws-setup
script-shell-backup-automation
```

### What NOT to Do ❌

| Bad Example | Issue | Better Alternative |
|-------------|-------|-------------------|
| `MyProject` | Not descriptive, PascalCase | `web-react-project-manager` |
| `app_v2` | Underscores, version number | `mobile-flutter-fitness` |
| `NewStuff` | Vague, no context | `lib-python-image-processing` |
| `project-2024` | Year in name | `web-saas-invoice-manager` |
| `john-api` | Personal name | `api-node-weather-service` |
| `EXPERIMENTAL PROJECT` | Spaces, all caps | `poc-rust-ml-engine` |
| `react_app_final_FINAL` | Underscores, redundant | `web-react-dashboard` |
| `dept-finance-tool` | Org structure | `web-expense-reporting` |
| `temp123` | Non-descriptive | `poc-python-data-pipeline` |
| `StudyProjectForLearningReact` | PascalCase, too long | `study-tutorial-react-basics` |

---

## Common Pitfalls to Avoid

### 1. **Over-Specifying**
❌ `web-react-typescript-redux-material-ui-ecommerce-app`  
✅ `web-react-ecommerce`

**Why:** Too many qualifiers make the name cumbersome. Use README badges or documentation for implementation details.

### 2. **Under-Specifying**
❌ `app` or `project` or `code`  
✅ `mobile-flutter-chat-app`

**Why:** Generic names provide zero context about the repository's purpose.

### 3. **Using Abbreviations**
❌ `web-rct-usr-mgmt-sys`  
✅ `web-react-user-management`

**Why:** Abbreviations reduce searchability and clarity for new team members.

### 4. **Mixing Case Styles**
❌ `Web-React-UserAuth` or `web_react_auth`  
✅ `web-react-user-auth`

**Why:** Consistency aids scanning and prevents confusion.

### 5. **Including Dates or Versions**
❌ `api-2024` or `project-v3`  
✅ `api-node-payment-service`

**Why:** Names should be stable. Use git tags and releases for versioning.

### 6. **Redundant Information**
❌ `python-script-python-automation`  
✅ `script-python-automation`

**Why:** Language is already specified; no need to repeat.

### 7. **Using Internal Jargon**
❌ `web-project-phoenix` (internal code name)  
✅ `web-react-analytics-dashboard`

**Why:** External contributors and future team members won't understand internal references.

---

## Renaming a GitHub Repository

Renaming a public GitHub repository is straightforward and safe. **You won't lose any internal data** such as commits, branches, issues, or wikis. GitHub automatically redirects from the old URL to the new one for web traffic, git operations, and API calls.

### Steps to Rename (GitHub Web Interface)

1. Navigate to your repository on GitHub
2. Click **Settings**
3. Scroll to the "Repository name" field
4. Enter the new name
5. Click **Rename**

---

## Updating Local Repositories After Rename

After renaming on GitHub, update your local clone to reflect the new URL:

### Using Git Command Line

1. **Update the remote URL:**
   ```bash
   git remote set-url origin https://github.com/your-username/new-repo-name.git
   ```

2. **Verify the change:**
   ```bash
   git remote -v
   ```
   
   This should display the new repository URL.

**Note:** GitHub automatically redirects git operations, but updating the remote URL ensures your local environment uses the correct path.

## Contributing

We welcome contributions! Here's how you can help:

- **Suggest new prefixes, types, or frameworks** by opening an issue
- **Share real-world examples** of the convention in use
- **Report inconsistencies or improvements** via pull requests
- **Translate documentation** into other languages
- **Build tools** that implement this standard

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## Roadmap

- [ ] Release v1.0 of the convention
- ✅ Build web-based name generator tool
- [ ] Create GitHub Action validator
- [ ] Publish npm package for CLI validation
- [ ] Develop VS Code extension
- [ ] Translate docs to Spanish, French, German, Japanese
- [ ] Partner with 10+ open source projects
- [ ] Reach 1,000 GitHub stars
- [ ] Get featured in GitHub's official blog

---

## Community

- **GitHub Discussions**: [Ask questions and share ideas](https://github.com/reslava/docs-repository-naming-convention/discussions)
- **Discord**: [Join our community](#) (coming soon)

---

## License

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This convention is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

---

## Acknowledgments

Inspired by best practices from the .NET, Node.js, Python, and Go communities. Special thanks to early adopters and contributors who help shape this standard.


---

<div align="center">

**⭐ Star this repository if you find it useful!**

Made with ❤️ by [Rafa Eslava](https://github.com/reslava) for developers

</div>