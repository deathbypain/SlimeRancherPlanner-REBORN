name: Bug Report
description: Report a bug or issue you've encountered
title: "[Bug] "
labels: ["bug"]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for reporting a bug! Please fill in the details below to help us understand and fix the issue.
  - type: textarea
    id: description
    attributes:
      label: Description
      description: Describe the bug you encountered
      placeholder: What happened?
    validations:
      required: true
  - type: textarea
    id: steps-to-reproduce
    attributes:
      label: Steps to Reproduce
      description: How can we reproduce the bug?
      placeholder: |
        1. Go to...
        2. Click on...
        3. See error...
    validations:
      required: true
  - type: textarea
    id: expected-behavior
    attributes:
      label: Expected Behavior
      description: What should have happened instead?
      placeholder: I expected...
    validations:
      required: true
  - type: textarea
    id: current-behavior
    attributes:
      label: Current Behavior
      description: What actually happened?
      placeholder: Instead...
    validations:
      required: true
  - type: textarea
    id: screenshots
    attributes:
      label: Screenshots (optional)
      description: Add screenshots to help illustrate the problem
  - type: textarea
    id: environment
    attributes:
      label: Environment
      description: Please provide details about your environment
      placeholder: |
        - Browser: 
        - OS: 
        - Version:
  - type: textarea
    id: additional-context
    attributes:
      label: Additional Context (optional)
      description: Any other details about the problem that may be relevant
