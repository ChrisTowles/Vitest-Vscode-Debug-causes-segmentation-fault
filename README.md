# Vitest basic - segment fault

So at work I've loved using vitest have had a problem where debugging is causing a segment fault. This repo is the result of trying to create in the simplest case.

## Recreate the problem

This is a clone of the [Vitest Basic Example](https://github.com/vitest-dev/vitest/tree/main/examples/basic)

All I've added is the `.vscode\launch.json` file.
exactly from <https://github.com/vitest-dev/vitest/blob/main/docs/guide/debugging.md>

## Steps to recreate the segment fault

Place a breakpoint in the `basic.test.ts` or `suite.test.ts` function.

run
