# Blueprint

This repository is a centralized JSON Schema library designed to eliminate configuration errors and establish a standardized data structure across my projects. By linking these schemas via the $schema property, you can enable real-time validation, auto-completion, and descriptive IntelliSense within VS Code.

## Quick Start

Add the $schema property to your JSON file:

{
  "$schema": "https://raw.githubusercontent.com/ferdikurnazdm/blueprint/refs/heads/main/schemas/your-schema.json"
}