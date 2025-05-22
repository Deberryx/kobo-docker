name: Bug report
description: Create a report to help us improve KoBo Docker
title: "[Bug]: "
labels: ["bug"]
assignees: []
body:
  - type: markdown
    attributes:
      value: |
        **Thanks for taking the time to file a bug!**  
        Please fill out every required field to help us reproduce.
  - type: textarea
    id: description
    attributes:
      label: Description
      placeholder: Clear and concise description of the problem…
    validations:
      required: true
  - type: textarea
    id: steps
    attributes:
      label: Steps to Reproduce
      placeholder: 1. … 2. …
    validations:
      required: true
  - type: textarea
    id: expected
    attributes:
      label: Expected Behaviour
      placeholder: What you expected to happen
  - type: textarea
    id: desktop
    attributes:
      label: Desktop / Server Details
      placeholder: |
        OS:
        Docker version:
        Docker-compose version:
        KoBo-docker release/tag:
  - type: textarea
    id: logs
    attributes:
      label: Logs / Screenshots
      placeholder: Paste relevant logs or screenshots here
