# Build Cevixe GitHub Actions

Build Cevixe GitHub Actions allows you to build cevixe projects

## Example usage

```yaml
on: [push]

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: protectasecurity/build-cevixe@v1
```
Output Artifact: dist

project

## Authors

- [Ronnie Ayala](https://github.com/ronnieacs)