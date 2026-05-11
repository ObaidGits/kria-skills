---
name: code_sandbox
description: Executes Python snippets in an isolated container and returns stdout.
category: developer
parameters:
  type: object
  properties:
    code:
      type: string
      description: Python code to run
  required: [code]
capabilities:
  network: false
  filesystem_read: false
  filesystem_write: false
  subprocess: true
---
