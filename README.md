# Text Editor Support for JOVIAL
Support for the JOVIAL/J73 standard in several modern text editors, based on MIL-STD-1589C. From Wikipedia:

> JOVIAL is a high-level programming language similar to ALGOL, specialized for developing embedded systems (specialized computer systems designed to perform one or a few dedicated functions, usually embedded as part of a larger, more complete device, including mechanical parts). It was a major system programming language through the 1960s and 70s. 
>
>**Most software implemented in JOVIAL is mission critical, and maintenance is growing more difficult.**

Given that JOVIAL will continue to be a major language in mission-critical software (at least until it is phased out), tools should exist to provide developers with basic Quality-of-Life while maintaining JOVIAL so as to prevent the errors that arise from coding in plain, unhighlighted text. 

## Installation
All installations begin with cloning the repository locally. After downloading, follow the instructions for the appropriate editor. 

### Visual Studio Code

### Notepad++

### Micro Editor

### Sublime Text 3
Copy the `JovialJ73/` folder to Sublime's `Packages` folder. This location varies by operating system.

Windows: (todo)

Linux: `~/.config/sublime-text-3/Packages`

macOS: `/Users/loganrios/Library/Application Support/Sublime Text 3/Packages`

When finished, package structure should look as such:

```
Packages
├── JovialJ73
│   └── JovialJ73.sublime-syntax
└── User
```

Restart Sublime and feel free to open/browse any `*.JOV` files. 

## TODO
- Support for function and variable names
- Automatic 'END' when user types 'BEGIN'
- Automatic 'TERM' when user types 'START'
- Better compiler directive highlighting (separate from keywords)
- Support for Jovial built-in functions
- Support for custom user types
- Sublime syntax test file
- Miscellaneous QoL improvements for Jovial coding
