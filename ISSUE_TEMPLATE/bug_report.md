name: Bug Report
description: Report something that's not working
title: "[BUG] <your bug title here>"
labels: [bug]
body:
  - type: textarea
    attributes:
      label: What happened?
      description: A clear and concise description of what the bug is.
    validations:
      required: true
  - type: textarea
    attributes:
      label: Steps to Reproduce
      placeholder: |
        1. Go to '...'
        2. Click on '....'
        3. See error
  - type: input
    attributes:
      label: Related Repository
      placeholder: e.g. algo-backend, frontend-dashboard
