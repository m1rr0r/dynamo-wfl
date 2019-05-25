# Dynamo Workflow Logic Language

This extenstion supports [Dynamo Software's](https://www.dynamosoftware.com/) domain specific language - Workflow Logic Language.

Supports files with extension "DWFL".

## Features

Intellisense for operation types and well-known input arguments:

![Intellisense](images/feature-intellisense-01.gif)

Check for valid operation types and operation names:

![Validate operation types](images/feature-operation-01.gif)

Hover over operations show documentaion:

![Documentation on hover](images/feature-hoverdoc-01.gif)

Code snippets:

![Snippets](images/feature-snippets-01.gif)

## Extension Settings

This extension contributes the following settings:

* `dynamoWorkflowLanguageServer.maxNumberOfProblems`: Controls the maximum number of problems produced by the server

## Known Issues

A lot of functionality is yet to be implemented! If you desperately need some helpful feature, or need a bug to be eradicate, please file an issue at [gitgub](https://github.com/m1rr0r/dynamo-wfl/issues).

## Release Notes

## 0.0.8
### Added
- Snippets for trigger, create and email operations

## 0.0.7
### Added
- Color theme support
- Hover documentation for some operations
- Improve intellisense context
