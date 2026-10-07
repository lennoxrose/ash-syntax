# Ash Language Support

Syntax highlighting for [Ash](https://github.com/lennoxrose/ash), a
small programming language with closures, hash maps, first-class functions,
and `attempt`/`handle`, built from scratch in C.

## Features

- Full syntax highlighting for `.ash` files: keywords, strings, numbers,
  function names, builtins, operators, comments, `@import` paths
- Bracket matching and auto-closing pairs for `{}`, `()`, and `[]`

## Example

```ash
forge clamp(value, min, max) {
    given value < min {
        yield min;
    }
    yield value;
}

local zone = zones[0];
say "zone: " + zone["name"];
```

## More

See the main [Ash repository](https://github.com/lennoxrose/ash) for the
language itself, the compiler/interpreter, and documentation.
