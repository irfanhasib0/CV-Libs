# Contributing to CV-Libs

Thank you for your interest in contributing to CV-Libs! This document provides guidelines for contributing to this repository.

## How to Contribute

### Adding a New Library

1. **Choose the Right Category**
   - Determine which category your library belongs to
   - If no category fits, suggest a new one in an issue

2. **Update Category README**
   - Add the library to the appropriate section
   - Include:
     - Library name
     - Brief description
     - Official link/repository
     - Installation command
     - Primary use cases
     - Example code snippet

3. **Update requirements.txt**
   - Add the library to the category's requirements.txt
   - Specify minimum version when important
   - Format: `package-name>=version`

### Adding a New Category

1. **Create Issue First**
   - Describe the new category
   - Explain why it doesn't fit existing categories
   - List at least 3-4 libraries that would belong

2. **Create Directory Structure**
   ```
   new_category/
   ├── README.md
   └── requirements.txt
   ```

3. **Update Main README**
   - Add category to the list
   - Include emoji and description
   - Link to the new category folder

## Guidelines

### Library Selection Criteria

Include libraries that are:
- ✅ Actively maintained (updated within last year)
- ✅ Well-documented
- ✅ Widely used or promising
- ✅ Open source or freely available
- ✅ Python-compatible (primary focus)

### README Format

Each category README should follow this structure:
```markdown
# Category Name

Brief description

## Categories
- Subcategory 1
- Subcategory 2

## Libraries

### Library Name
- **Description**: Brief description
- **Link**: Official URL
- **Install**: Installation command
- **Use Cases**: Primary use cases

## Example Usage
```python
# Code example
```
```

### Code Examples

- Keep examples simple and self-contained
- Use common variable names
- Include necessary imports
- Test that examples work

## Pull Request Process

1. **Fork and Branch**
   ```bash
   git checkout -b feature/add-new-library
   ```

2. **Make Changes**
   - Follow the guidelines above
   - Keep changes focused and minimal

3. **Test**
   - Verify links work
   - Check that code examples are correct
   - Ensure requirements.txt is valid

4. **Submit PR**
   - Clear title describing the change
   - Description of what was added/changed
   - Reference any related issues

## Code of Conduct

- Be respectful and constructive
- Focus on what is best for the community
- Welcome newcomers and encourage diverse perspectives

## Questions?

- Open an issue for discussion
- Check existing issues for similar questions

Thank you for contributing! 🎉
