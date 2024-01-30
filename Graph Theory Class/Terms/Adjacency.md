Given two [[Vertex|vertices]] `u & v` if the [[Edge]] `{u,v}` exist in the set of edges `E` then they are considered adjacent

## Example
| V | E |
| --- | --- |
| a,b,c | {a,b},{b,c} |
```mermaid
graph LR;
a---b;
b---c;
```
| Vertex | Adjacent to |
| ---- | ---- |
| a | b |
| b | b,c |
| c | b |
