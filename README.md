# UBL 2.1 Documentation

Interactive documentation for OASIS UBL 2.1 Invoice schema.

## Features

- Complete UBL 2.1 Invoice schema coverage
- Interactive tree view - click to expand/collapse nodes
- Smart search - finds fields in names and descriptions (min 2 chars)
- Search includes nested fields from type definitions
- Enum values for code lists (currency, country, etc.)
- Alternating row backgrounds by depth level
- Aligned columns: Field Name | Card. | Description

## Bug Fixes

### Fixed crashes:
1. **Cycle detection** - Added tracking of visited type definitions to prevent infinite loops
2. **Search limit** - Limited to 200 results to prevent UI freeze
3. **Depth limit** - Maximum 8 levels deep to prevent stack overflow
4. **Iterative search** - Using stack instead of recursion to avoid call stack overflow
5. **Expand All** - Now works without crashing

## GitHub Pages Setup

1. Create a new repository on GitHub
2. Upload all files from this folder to the repository
3. Go to Settings → Pages
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click Save

## Live Demo

https://dmubgmzatdrjc.ok.kimi.link
