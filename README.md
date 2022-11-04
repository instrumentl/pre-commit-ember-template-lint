This repository contains glue to make [ember-template-lint](https://github.com/ember-template-lint/ember-template-lint)
work with [pre-commit](https://pre-commit.com/).

To use, add the following to your `.pre-commit-config.yaml`:

```yaml
  - repo: https://github.com/instrumentl/pre-commit-ember-template-lint.git
    rev: 'v1.0'
    hooks:
    -  id: ember-template-lint
       additional_dependencies: ['ember-template-lint@4.17.0']
```
