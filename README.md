# array-flatten

Flatten a multi-dimensional array for Deno.

![CI](https://github.com/namelos/array-flatten/workflows/CI/badge.svg)

## Examples

```ts
import flatten from 'https://deno.land/x/array-flatten/mod.ts'

flatten([1, [2, [3, [4, [5, 6]]]]]) // => [1, 2, 3, 4, 5, 6]
```
