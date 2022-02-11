# Vitest basic - Vscode Debug causes segmentation fault

So at work I've loved using vitest have had a problem where debugging is causing a segment fault. This repo is the result of trying to create in the simplest case.

## Recreate the problem

This is a clone of the [Vitest Basic Example](https://github.com/vitest-dev/vitest/tree/main/examples/basic)

All I've added is the `.vscode\launch.json` file.
Exactly from <https://github.com/vitest-dev/vitest/blob/main/docs/guide/debugging.md>

## Steps to recreate the segmentation fault

Place a breakpoint in the `basic.test.ts` or `suite.test.ts` function.

Use the VsCode launcher to debug the selected test file.

Video showing it segmentation fault, remove the breakpoint it works, putting it back and segmentation faults again.

![show-seg-vault](/show-seg-vault-2022-02-10-20-03.gif)
