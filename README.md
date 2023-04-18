# Jaeger Tracing Setup Guide

Jaeger Tracing Setup Guide

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install jaeger.

```bash
pip install jaeger-client opentracing-instrumentation
```

```bash
docker run -d -p 6831:6831/udp -p 16686:16686 jaegertracing/all-in-one:latest
```


## Usage

```python
import jaeger_client
from jaeger_client import Config
```



