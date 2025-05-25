

# Getting started with bblocks

This guide will help you get up and running with bblocks in just a few steps.

## Installation
You can install bblocks in several ways, depending on your needs:


```bash title="Install the entire bblocks suite"
pip install bblocks
```

```bash title="Install a specific package"
pip install bblocks[clean]
```

Install everything (all optional dependencies):

```bash title="Install all optional dependencies"
pip install bblocks[all]
```

```bash title="Install a single package"
pip install bblocks-clean
```
`

## Basic Usage

Here’s a simple example showing how to use one of the tools in the clean package.

```python
from bblocks.clean import clean_number

number = "1,435,660.45"

clean_number(number)
# Output: 1435660.45
```
This utility function takes a string representation of a number—including commas or other formatting—and converts it to a clean, numeric format.