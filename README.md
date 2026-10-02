# Ash Language Support

Syntax highlighting for [Ash](https://github.com/lennoxrose/ash), a
small programming language with closures, hash maps, first-class functions,
and `try`/`catch`, built from scratch in C.

## Features

- Full syntax highlighting for `.ash` files: keywords, strings, numbers,
  function names, operators, comments
- Bracket matching and auto-closing pairs

## Example

```ash
fn make_adder(x) {
    return fn(y) { return x + y; };
}

let add5 = make_adder(5);
print add5(3); // 8
```

## More

See the main [Ash repository](https://github.com/lennoxrose/ash) for the
language itself, the compiler/interpreter, and documentation.
