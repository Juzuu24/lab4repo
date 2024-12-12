---
name: Bug report
about: Report a bug to help us improve the project.
title: '[bug]'
labels: 'bug'
assignees: ''
body:
  - type: textarea
    id: description
    attributes:
      label: Bug description
      description: Provide a clear and concise description of the issue.
      placeholder: Describe the bug here...
  - type: select
    id: severity
    attributes:
      label: Severity
      options:
        - Low
        - Medium
        - High
  - type: checkboxes
    id: reproducibility
    attributes:
      label: Steps to reproduce
      description: Check all that apply.
      options:
        - label: Happens every time
        - label: Happens occasionally
        - label: Unable to reproduce
---
