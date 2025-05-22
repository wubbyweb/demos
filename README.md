# DuckDuckGo Search Jupyter Notebook

A simple Jupyter notebook that demonstrates how to use the DuckDuckGo Search API to perform web searches programmatically.

## Overview

This project contains a Jupyter notebook (`duckduckgo.ipynb`) that shows how to:
- Install the DuckDuckGo Search package
- Perform text searches using the DDGS API
- Process and display search results

## Prerequisites

- Python 3.x
- Jupyter Notebook or Jupyter Lab
- Internet connection

## Installation

The notebook automatically installs the required package, but you can also install it manually:

```bash
pip install duckduckgo-search
```

## Usage

1. Open the `duckduckgo.ipynb` notebook in Jupyter
2. Run all cells to see the search in action
3. Modify the search query to experiment with different searches

## Example

The current example searches for "write a sample program using google A2A framework" and returns up to 5 results.

```python
from duckduckgo_search import DDGS

results = DDGS().text("write a sample program using google A2A framework", max_results=5)
print(results)
```

## Features

- No API key required
- Simple and easy to use
- Configurable number of results
- Access to DuckDuckGo's search results

## Additional Information

The [duckduckgo-search](https://github.com/deedy5/duckduckgo_search) package provides various search methods including:
- Text search
- News search
- Image search
- Video search
- And more

## License

This project is provided as a demonstration. Check the duckduckgo-search package for its license details.