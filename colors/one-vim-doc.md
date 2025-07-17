# one-vim.vim Theme Documentation

## Overview

This document describes the current state of the `one-vim.vim` color scheme for Vim, inspired by the Atom One theme. The theme aims to provide a visually consistent and modern experience for Vim users, supporting both dark and light backgrounds. It is designed to work seamlessly with Vim and Neovim, including terminal color support and plugin-specific highlights.

## Supported Languages and Syntax Groups

The theme provides explicit highlight definitions and links for a wide range of programming languages and file types. Below is a summary of supported languages and the level of support:

### 1. Core Vim Syntax
- **Full Support**: All standard Vim highlight groups (Normal, Comment, Constant, String, Function, Statement, Type, etc.) are defined with custom colors and styles.

### 2. Programming Languages
- **JavaScript**: Extensive support, including ES6+ features and JSX (with vim-jsx-pretty). All major syntax groups and keywords are covered.
- **JSX**: Dedicated highlight links for tags, attributes, braces, and embedded JavaScript.
- **Rust**: Comprehensive support for keywords, types, lifetimes, attributes, comments, and error/warning groups.
- **Haskell**: Full coverage for types, identifiers, keywords, numbers, strings, comments, constructors, operators, pragmas, errors, and warnings.
- **Python**: All major syntax groups, including statements, builtins, functions, classes, operators, keywords, decorators, strings, numbers, comments, self, docstrings, exceptions, errors, warnings, and string formatting.
- **Ruby**: Complete support for classes, functions, keywords, symbols, constants, strings, numbers, comments, modules, tests, regex, errors, and warnings.
- **PHP**: Basic support for classes, functions, keywords, and types.
- **Go**: Support for declarations, types, and methods.

### 3. Markup and Data Languages
- **HTML**: Highlights for arguments, tag names, tags, and end tags.
- **CSS**: Support for class names, properties, tag names, and string types.
- **JSON**: Coverage for keywords, strings, numbers, and booleans.
- **Markdown**: Highlights for code, code blocks, headings (H1-H6), bold, and italic text.

### 4. Vim Script
- **VimL**: Support for commands, functions, function names, highlights, and variables.

### 5. Git Commit Messages
- **Git**: Highlights for comments, branch names, selected/discarded/unmerged files.

### 6. Miscellaneous
- **Spelling**: Support for bad, local, capitalized, and rare spelling errors.
- **Plugin Support**: Specific highlights for NERDTree and ALE plugins.
- **Diff**: Dedicated colors for added, changed, deleted, and text regions in diffs.

## Terminal Color Support

The theme sets terminal colors for Neovim, ensuring consistency between GUI and terminal environments. Sixteen terminal colors are defined, matching the theme's palette.

## Customization and Options

- **Transparent Background**: The theme respects the `g:one_nvim_transparent_bg` global variable, allowing users to enable a transparent background.
- **Background Detection**: Automatically adjusts color palette based on Vim's `background` setting (`dark` or `light`).

## Limitations and Known Issues

- **Language Support**: While the theme covers many popular languages, support for less common languages may be limited or rely on default Vim highlight groups.
- **Plugin Integration**: Only a few plugins (NERDTree, ALE) have dedicated highlight groups. Additional plugin support may require manual configuration.
- **Terminal Colors**: Terminal color definitions are only set for Neovim (`has('nvim')`). Vim users may need to configure terminal colors separately.

## Maintenance

The theme is actively maintained and open to contributions. For issues or feature requests, please contact the author or submit a pull request.
