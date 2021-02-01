[![npm version](https://badge.fury.io/js/%40shlappas%2Ftuple-type.svg)](https://badge.fury.io/js/%40shlappas%2Ftuple-type)

# Tuple Type

Sometimes it would be nice to specify a length for a tuple in typescript instead
of explicitly typing it out. For example:

```ts
// like
type Foo = Tuple<number, 5>

// instead of
type Foo = [number, number, number, number, number]
```

This package provides exactly that. Simple!

## Installation

```bash
yarn add @shlappas/tuple-type
```
