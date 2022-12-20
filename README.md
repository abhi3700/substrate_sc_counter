# Counter

Counter SC using ink!

## Overview

- A counter SC that can be incremented and decremented.
- Functions:
  - `new` - Initializes the counter with the specified value.
  - `default` - Initializes the counter with the default value of 0.
  - `inc` - Increments the counter by 1.
  - `dec` - Decrements the counter by 1.
  - `get_val` - Returns the current value of the counter.

## Test

```bash
cargo test
```

## Build

```bash
cargo +nightly contract build
```

## Deploy

<!-- TODO: add command-->
