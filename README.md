# Global CodeRabbit Configuration

This repository contains the global configuration for [CodeRabbit](https://coderabbit.ai/), an AI-powered code review tool. 

The `.coderabbit.yaml` file in this repository acts as the central source of truth for all my open-source projects. It ensures that the AI:
- Acts as a supportive Python mentor.
- Focuses on logic, architecture, and security rather than stylistic nitpicks.
- Defers to `ruff` and `uv` for all formatting, linting, and dependency management.

By keeping this configuration here, CodeRabbit automatically inherits these rules across all my repositories without needing to duplicate the YAML file in every project.
