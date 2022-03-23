# Terraform Lint Action

```yaml
name: Terraform Lint

on: [push, pull_request]

jobs:
  terraform-lint:
    runs-on: ubuntu-latest
    steps:

    - name: Checkout
      uses: actions/checkout@v3

    - name: Terraform Lint
      uses: ShubhamTatvamasi/terraform-lint-action@v1
```
