# TravBotGH

The code for TravBotGH.

This action is currently just a copy of NodeCodeFormatter to see how GitHub Actions work.

It needs a `lint` or `format` NPM/Yarn script.

## Example usage

```yaml
on: push
name: Node Code Formatter
jobs:
  lint:
    name: TravBotGH
    runs-on: ubuntu-latest
    steps:
    - name: Code formatter
      uses: keanuplayz/TravBot-GH@stable
      env:
        GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```
