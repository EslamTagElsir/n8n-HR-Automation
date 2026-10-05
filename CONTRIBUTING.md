# Contributing to n8n HR Automation

Thank you for your interest in contributing! 🎉

## How to Contribute

### Reporting Issues
- Use the [GitHub Issues](https://github.com/EslamTagElsir/n8n-HR-Automation/issues) tab
- Include your n8n version, workflow name, and steps to reproduce

### Suggesting Features
- Open an issue with the `enhancement` label
- Describe the use case and expected behavior

### Submitting Changes

1. **Fork** the repository
2. **Create** a feature branch from `main`:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make** your changes
4. **Test** your workflow changes by importing into n8n and running them
5. **Export** the updated workflow as JSON (Settings → Export)
6. **Commit** with a clear message:
   ```bash
   git commit -m "feat: add interview reminder workflow"
   ```
7. **Push** and open a Pull Request

### Workflow Export Guidelines

When exporting n8n workflows for contribution:

- ⚠️ **Remove all credentials** — Never include API keys, OAuth tokens, or personal data
- ⚠️ **Replace personal emails** — Use `your-email@example.com` as a placeholder
- ⚠️ **Replace sheet URLs** — Use `YOUR_GOOGLE_SHEET_URL` as a placeholder
- ⚠️ **Replace webhook URLs** — Use `YOUR_N8N_INSTANCE_URL` as a placeholder
- ✅ **Keep node notes** — They help others understand the workflow logic
- ✅ **Use descriptive node names** — e.g., "Validate PDF File" not "Code1"

### Commit Message Convention

We follow [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` — New feature or workflow
- `fix:` — Bug fix
- `docs:` — Documentation changes
- `refactor:` — Code restructuring without behavior change
- `style:` — Formatting, naming, etc.

## Code of Conduct

- Be respectful and constructive
- Focus on the problem, not the person
- Welcome newcomers

Thank you for helping make this project better! 🚀
