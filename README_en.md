# Sogou Search API

An unofficial Python API to get search results from Sogou.

## Installation

```bash
pip install k-sogou-search
```

## Usage

```python
from sogou_search import sogou_search

results = sogou_search('人工智能', num_results=15)
for result in results:
    print(result)
```
