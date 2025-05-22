This change will trigger a workflow run based on these path filters:

```yaml
paths:
  # include markdown files
  - "02-mechanics-core/filters/*.md"
  # Exclude txt files
  - "!02-mechanics-core/filters/*.txt"
```
