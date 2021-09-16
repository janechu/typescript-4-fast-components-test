# typescript-4-fast-components-test
This is a temporary repository to tests a scenario where typescript 4 causes errors when building a project containing `@microsoft/fast-components`.

## Repro steps

- In a terminal, run the command `npm run tsc`. This will attempt to compile the `index.ts` which imports the `@microsoft/fast-components` and use the locally installed TypeScript 4+.
- The errors should show up in the terminal.
