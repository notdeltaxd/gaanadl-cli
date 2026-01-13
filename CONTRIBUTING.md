# Contributing to Gaana CLI

Thanks for your interest in contributing! Here's how you can help.

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR_USERNAME/gaana-cli.git`
3. Create a branch: `git checkout -b feature/your-feature`
4. Install dev dependencies: `pip install -e .`

## Development

```bash
# Run locally
python -m gaana.cli manjha

# Test a specific feature  
gaana -s "arijit" --show-results
```

## Pull Requests

- Keep changes focused and atomic
- Update README if adding features
- Test your changes before submitting

## Issues

- Search existing issues first
- Include reproduction steps for bugs
- Be specific about your environment (OS, Python version)

## Code Style

- Follow PEP 8
- Use type hints where helpful
- Keep functions focused and well-named
