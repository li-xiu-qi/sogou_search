# Sogou Search API

An unofficial Python API to get search results from Sogou.

## Installation

```bash
pip install sogou_search_lixiuqi
```

## Usage

```python
from sogou_search import sogou_search_api

results = sogou_search_api('人工智能', num_results=15)
for result in results:
    print(result)
```
