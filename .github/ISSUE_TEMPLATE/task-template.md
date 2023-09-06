name: Task Template
about: Developer defined task.
title: "[Task]: "
labels: documentation
assignees: ''
body:
- type: markdown
  attributes:
    value: |
      hey bro.
- type: dropdown
  id: labels
  attributes:
    label: This is my label.
    multiple: false
    options:
      - Option 1
      - Option 2
