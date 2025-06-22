# 🤝 Contributing to FarmVille 2 Offline Setup Assistant

Thank you for your interest in contributing to our project! This setup assistant helps players enjoy FarmVille 2: Country Escape completely offline, and your contributions make it better for everyone.

## 🌟 Ways to Contribute

### 🐛 Bug Reports
Found an issue? Help us fix it!
- Use clear, descriptive titles
- Include system information (OS, version)
- Provide step-by-step reproduction steps
- Attach screenshots or error logs if relevant

### 💡 Feature Requests
Have ideas for improvements?
- Explain the problem your feature would solve
- Describe your proposed solution
- Consider alternative solutions
- Explain why this would benefit the community

### 🌍 Translations
Help make the setup assistant accessible worldwide!
- See our [Translation Guide](docs/TRANSLATION_GUIDE.md)
- Current priority languages: Spanish, French, German, Portuguese
- We use simple JSON files for translations

### 📚 Documentation
Improve our guides and help content:
- Fix typos or unclear instructions
- Add troubleshooting steps for common issues
- Create video tutorials or guides
- Update system requirements or compatibility info

### 🔧 Code Contributions
Improve the setup assistant functionality:
- Bug fixes and performance improvements
- New configuration options
- Better error handling
- Cross-platform compatibility fixes

## 🚀 Getting Started

### Development Setup
1. **Fork** this repository to your GitHub account
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/farmville2-country-escape-offline-setup-assistant.git
   cd farmville2-country-escape-offline-setup-assistant
   ```
3. **Install** development dependencies:
   ```bash
   pip install -r requirements-dev.txt
   ```

### Development Environment
- **Python**: 3.8+ required
- **IDE**: Visual Studio Code recommended
- **Tools**: Git, 7-Zip (for testing archives)
- **Testing**: Windows VM recommended for cross-platform testing

## 📝 Coding Standards

### Python Style
- Follow **PEP 8** style guidelines
- Use **type hints** for function parameters and returns
- Write **docstrings** for all functions and classes
- Keep functions focused and under 50 lines when possible

### Example Code Style
```python
def configure_display_settings(resolution: tuple[int, int], fullscreen: bool) -> bool:
    """
    Configure display settings for the game.
    
    Args:
        resolution: Tuple of (width, height) for display resolution
        fullscreen: Whether to enable fullscreen mode
        
    Returns:
        bool: True if configuration was successful, False otherwise
    """
    try:
        # Implementation here
        return True
    except Exception as e:
        logger.error(f"Failed to configure display: {e}")
        return False
```

### Commit Messages
Use clear, descriptive commit messages:
- `feat:` for new features
- `fix:` for bug fixes
- `docs:` for documentation changes
- `refactor:` for code improvements
- `test:` for test additions

Examples:
```
feat: add support for 4K resolution configuration
fix: resolve crash when selecting invalid language
docs: update installation guide for macOS users
```

## 🧪 Testing

### Before Submitting
- Test your changes on multiple platforms if possible
- Verify the setup assistant still works correctly
- Check that all existing functionality remains intact
- Run any available automated tests

### Testing Checklist
- [ ] Setup assistant launches without errors
- [ ] Configuration options work as expected
- [ ] Changes don't break existing functionality
- [ ] Documentation is updated if needed
- [ ] Code follows project style guidelines

## 📋 Pull Request Process

### 1. Prepare Your Changes
- Create a feature branch from `main`
- Make your changes in focused, logical commits
- Update documentation as needed
- Test thoroughly on your platform

### 2. Submit Pull Request
- Use our [PR template](.github/PULL_REQUEST_TEMPLATE.md)
- Provide clear description of changes
- Link any related issues
- Add screenshots for UI changes

### 3. Review Process
- Maintainers will review your PR
- Address any requested changes
- Once approved, your PR will be merged
- Thank you for contributing! 🎉

## 🛡️ Code of Conduct

### Our Pledge
We're committed to providing a welcoming, inclusive environment for all contributors, regardless of background, experience level, or identity.

### Expected Behavior
- **Be respectful** in all interactions
- **Be constructive** in feedback and discussions
- **Be patient** with newcomers and different skill levels
- **Focus on collaboration** and helping each other

### Unacceptable Behavior
- Harassment, discrimination, or hostile behavior
- Spam, trolling, or deliberately disruptive behavior
- Sharing inappropriate content
- Violating others' privacy or safety

## 🏆 Recognition

### Contributors
All contributors are recognized in our:
- [README.md](README.md) credits section
- [Contributors page](https://github.com/FarmVille-2-Country-Escape-Offline-Free/farmville2-country-escape-offline-setup-assistant/graphs/contributors)
- Release notes for significant contributions

### Maintainer Path
Active, helpful contributors may be invited to become maintainers with additional repository access and responsibilities.

## ❓ Questions?

### Get Help
- 💬 [Discussions](https://github.com/FarmVille-2-Country-Escape-Offline-Free/farmville2-country-escape-offline-setup-assistant/discussions) - General questions
- 🐛 [Issues](https://github.com/FarmVille-2-Country-Escape-Offline-Free/farmville2-country-escape-offline-setup-assistant/issues) - Bug reports and feature requests
- 📧 Email: maintainers@farmville2offline.com

### Development Resources
- [Technical Documentation](docs/TECHNICAL.md)
- [API Reference](docs/API.md)
- [Architecture Overview](docs/ARCHITECTURE.md)

---

**Thank you for helping make FarmVille 2 accessible to everyone! Your contributions make a real difference in the gaming community.** 🚜❤️ 