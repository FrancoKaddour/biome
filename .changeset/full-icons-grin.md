---
"@biomejs/biome": patch
---

Fixed [#11528](https://github.com/biomejs/biome/issues/11528): [`noFloatingPromises`](https://biomejs.dev/linter/rules/no-floating-promises/) no longer reports statement-level `await` expressions, including overloaded calls returning Promise aliases and awaited values that resolve to arrays of Promises.
