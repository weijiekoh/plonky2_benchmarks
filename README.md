# plonky2 benchmarks

## Pure plonky2

This repo runs a very simple benchmark for the plonky2 proving system for
generating proofs of computation of an $n$th Fibonacci number.

```bash
cargo run --release
```

## Results

On an Intel 13th Gen Intel(R) Core(TM) i7-13700HX running Ubuntu Linux:

```
Pure-plonky2 proof generation time for Fib 2^10: 54 ms
Pure-plonky2 proof generation time for Fib 2^11: 12 ms
Pure-plonky2 proof generation time for Fib 2^12: 14 ms
Pure-plonky2 proof generation time for Fib 2^13: 29 ms
Pure-plonky2 proof generation time for Fib 2^14: 51 ms
Pure-plonky2 proof generation time for Fib 2^15: 131 ms
Pure-plonky2 proof generation time for Fib 2^16: 215 ms
Pure-plonky2 proof generation time for Fib 2^17: 371 ms
Pure-plonky2 proof generation time for Fib 2^18: 763 ms
Pure-plonky2 proof generation time for Fib 2^19: 1677 ms
Pure-plonky2 proof generation time for Fib 2^20: 3438 ms
```
