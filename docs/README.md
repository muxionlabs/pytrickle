# PyTrickle Documentation

This directory contains the documentation website for PyTrickle, hosted on GitHub Pages.

## Files

- **index.html** - Main documentation page with installation, CLI guide, and examples
- **codemap.html** - Detailed code architecture, module reference, and workflow guide
- **styles.css** - Stylesheet for both pages

## Local Development

To view the documentation locally:

1. Open `index.html` in your web browser, or
2. Run a local web server:
   ```bash
   cd docs
   python -m http.server 8080
   ```
   Then visit http://localhost:8080

## Deployment

The documentation is automatically deployed to GitHub Pages when changes are pushed to the `main` branch via the `.github/workflows/deploy-docs.yml` workflow.

## Structure

The documentation consists of:

### Main Page (index.html)
- Overview and features
- Installation instructions
- CLI guide (pytrickle init, pytrickle list)
- Template descriptions
- Code examples
- Pipeline creation tutorial
- HTTP API reference

### Code Map (codemap.html)
- System architecture diagram
- Core components overview
- Module reference
- Frame object specifications
- Decorator API guide
- Pipeline workflow

## Contributing

To update the documentation:

1. Edit the HTML or CSS files in this directory
2. Test locally to ensure changes look correct
3. Commit and push to trigger automatic deployment
