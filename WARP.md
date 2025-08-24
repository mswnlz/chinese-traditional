# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Project Overview

This is a Chinese traditional culture resource repository (`mswnlz/chinese-traditional`) that serves as a curated collection of traditional culture knowledge, historical materials, and cultural heritage content.

## Common Commands

### Resource Management
```bash
# Create new monthly resource file
touch $(date +%Y%m).md

# View recent resource files
ls -la 2025*.md | head -5

# Search for traditional culture topics
grep -r "传统文化" *.md
grep -r "traditional" *.md
```

## Content Guidelines

- Use consistent formatting with descriptive titles
- Include proper attribution with "超过100T资料总站网站-doc.869hr.uk" suffix
- Organize resources by cultural category and historical period
- Provide both Chinese and English descriptions where applicable
