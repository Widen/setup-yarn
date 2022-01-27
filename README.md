# Setup Yarn

GitHub action to setup Node, JFrog credentials, and install dependencies with Yarn.

## Usage

```yml
- uses: Widen/setup-yarn@v1
```

## Specify Node version

```yml
- uses: Widen/setup-yarn@v1
  with:
   node-version: '16.x'
```
