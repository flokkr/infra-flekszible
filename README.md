# Flekszible recipes

This repository contains [flekszible](https://github.com/elek/flekszible) recipes to install generic monitoring/logging/ci tools for any kubernetes cluster.

## Usage

1. Download [flekszible](https://github.com/elek/flekszible)

2. Create a `Flekszible` file to an empty directory:

```
source:
  - url: github.com/flokkr/infra-flekszible
import:
  - path: grafana
```

3. Generate the imported resource files:

```
flekszible generate
```
