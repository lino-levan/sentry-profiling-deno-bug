# `@sentry/profiling-node` Deno 2.0.2 support bug

1. Clone this this
2. Run `deno install --allow-scripts`

```
error: script 'install' in '@sentry/profiling-node@8.34.0' failed with exit code 1
stdout:
@sentry/profiling-node: Precompiled binary found, attempting to load /Users/linolevan/Desktop/test-deno-npm/node_modules/.deno/@sentry+profiling-node@8.34.0/node_modules/@sentry/profiling-node/lib/sentry_cpu_profiler-darwin-arm64-108.node

stderr:
dyld[31675]: missing symbol called
```
