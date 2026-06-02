# Meet Z3

**Minimalist S3 server in Zig with No AI slop.**

[View on GitHub](https://github.com/getz3/z3)

## Why Z3?

Built for the ultimate minimalist S3 experience.

- **Small**

  Extremely small boot footprint, using less than 2MB of memory.

- **Fast**

  Blazing-fast performance powered by Zig and Async ZIO.

- **Clean**

  Built on a multi-role finite state machine with no AI slop.

## Quick Start

```shell
# Build
zig build -Doptimize=ReleaseFast

# Run
./zig-out/bin/z3

# Options
./zig-out/bin/z3 --port=9000 --data-dir=./data --tmp=./tmp
```

## FAQ

### What is Z3?

Z3 is a minimalist S3 server in Zig, built for local development and testing.

### Is Z3 distributed?

No. Z3 is, and will remain, a single-node server optimized for local development and testing.

### Is Z3 ready for production use?

No. Z3 is in the early stages of active development.

### Why Zig?

Zig compiles to tiny, fast binaries, giving Z3 near-instant boot times and minimal memory usage.
