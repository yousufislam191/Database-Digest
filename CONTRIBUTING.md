# Contributing to Database-Digest

Thank you for your interest in contributing to Database-Digest! We welcome contributions from database enthusiasts, engineers, and learners of all levels.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Article Guidelines](#article-guidelines)
- [Getting Started](#getting-started)
- [Submission Process](#submission-process)
- [Style Guide](#style-guide)
- [Review Process](#review-process)

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## How Can I Contribute?

### 📝 Writing Articles
- Create in-depth articles about database concepts, techniques, or best practices
- Update existing articles with new information or improvements
- Translate articles to other languages

### 🐛 Reporting Issues
- Report typos, grammatical errors, or technical inaccuracies
- Suggest improvements to existing content
- Request new topics or articles

### 💡 Suggesting Topics
- Propose new database topics that would benefit the community
- Share interesting use cases or real-world scenarios

### 🔍 Reviewing Content
- Help review pull requests for technical accuracy
- Provide feedback on article clarity and structure

## Article Guidelines

### Content Requirements
- **Accuracy**: All technical information must be accurate and up-to-date
- **Clarity**: Articles should be clear, well-structured, and accessible to the target audience
- **Completeness**: Cover the topic comprehensively with practical examples
- **Originality**: Content should be original or properly attributed

### Target Audience
Articles should be written for:
- Database administrators and engineers
- Software developers working with databases
- Students learning database concepts
- Anyone interested in data management

### Technical Standards
- Use proper SQL syntax highlighting
- Include practical, working examples
- Provide explanations for complex concepts
- Add relevant diagrams or images when helpful

## Getting Started

### Prerequisites
- Basic knowledge of databases and SQL
- Familiarity with Git and GitHub
- Markdown writing skills

### Setting Up Your Environment
1. Fork the repository
2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Database-Digest.git
   cd Database-Digest
   ```
3. Create a new branch for your contribution:
   ```bash
   git checkout -b feature/your-article-topic
   ```

## Submission Process

### For New Articles

1. **Create Article Directory**
   ```
   articles/
   ├── your-topic-name/
   │   ├── README.md          # Main article content
   │   └── images/           # Supporting images (if any)
   │       ├── diagram1.png
   │       └── example.jpg
   ```

2. **Article Structure**
   Your `README.md` should follow this structure:
   ```markdown
   # Article Title
   
   Brief introduction paragraph.
   
   ## Table of Contents
   - [Section 1](#section-1)
   - [Section 2](#section-2)
   
   ## Introduction
   Detailed introduction...
   
   ## Main Content
   Your article content with examples...
   
   ## Conclusion
   Summary and key takeaways...
   
   ## References
   - Link 1
   - Link 2
   ```

3. **Update Main README**
   Add your article to the articles table in the main README.md

4. **Submit Pull Request**
   - Commit your changes with clear, descriptive messages
   - Push to your fork
   - Create a pull request with a detailed description

### For Updates to Existing Articles

1. Make your changes to the existing article
2. Ensure all information remains accurate
3. Test any code examples
4. Submit a pull request with a clear description of changes

## Style Guide

### Writing Style
- Use clear, concise language
- Write in active voice when possible
- Use proper grammar and spelling
- Be inclusive and welcoming in tone

### Code Examples
- Use proper syntax highlighting:
  ```sql
  SELECT column_name
  FROM table_name
  WHERE condition;
  ```
- Include comments for complex queries
- Test all code examples before submission

### Images and Diagrams
- Use descriptive filenames
- Optimize images for web (reasonable file sizes)
- Include alt text for accessibility
- Store images in the `images/` folder within your article directory

### Markdown Formatting
- Use proper heading hierarchy (H1 for title, H2 for main sections)
- Use bullet points and numbered lists appropriately
- Include a table of contents for longer articles
- Use code blocks for SQL/code snippets

## Review Process

### What to Expect
1. **Initial Review**: Maintainers will review your submission within 1 week
2. **Feedback**: You may receive requests for changes or improvements
3. **Technical Review**: Content will be checked for technical accuracy
4. **Final Approval**: Once approved, your contribution will be merged

### Review Criteria
- Technical accuracy and completeness
- Writing quality and clarity
- Adherence to style guidelines
- Proper formatting and structure
- Relevance to the project's goals

## Questions or Need Help?

- Open an issue for questions about contributing
- Check existing issues and pull requests
- Review the [Code of Conduct](CODE_OF_CONDUCT.md)

## Recognition

Contributors will be acknowledged in:
- The main README.md file
- Individual article acknowledgments
- GitHub contributor statistics

Thank you for helping make Database-Digest a valuable resource for the database community! 🚀