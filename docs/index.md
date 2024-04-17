# Seja Muito Bem Vindo!

## Código de testes

```python
from fastapi import Fastapi

app = Fastapi()

@app.get('/')
def hello_world() -> str:
  return "Hello World!"
```


[Código de Testes](#código-de-testes)