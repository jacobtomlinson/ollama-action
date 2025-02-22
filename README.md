# ollama

[![version](https://badgen.net/github/release/ai-action/ollama)](https://github.com/ai-action/ollama/releases)
[![test](https://github.com/ai-action/ollama/actions/workflows/test.yml/badge.svg)](https://github.com/ai-action/ollama/actions/workflows/test.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

🦙 Run [Ollama](https://ollama.com/) large language models in GitHub Actions.

## Quick Start

```yaml
# .github/workflows/ollama.yml
on: push
jobs:
  ollama:
    runs-on: ubuntu-latest
    steps:
      - name: Run LLM
        uses: ai-action/ollama@v1
```

## Usage

**Basic:**

```yaml
- uses: ai-action/ollama@v1
```

See [action.yml](action.yml)

## Inputs

### `version`

**Optional**: The version. Defaults to `1.2.3`:

```yaml
- uses: ai-action/ollama@v1
  with:
    version: 1.2.3
```

## License

[MIT](LICENSE)
