---
layout: default
title: Installation
nav_order: 8
description: "How to install llm-contracts"
---

# Installation

## Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

## Installation Options

### From PyPI (Recommended)

```bash
pip install llm-contracts
```

### From GitHub (Development Version)

For the latest development version:

```bash
# Clone the repository
git clone https://github.com/Maxamed/llm-contract.git
cd llm-contracts

# Install in development mode
pip install -e .
```

## Verify Installation

After installation, you can verify that llm-contracts is working correctly:

```bash
# Check the CLI is available
llm-validate --help
```

You should see the help output for the llm-validate command.

## Next Steps

Once you've installed llm-contracts, head over to the [Getting Started](getting-started) guide to learn how to use it. 