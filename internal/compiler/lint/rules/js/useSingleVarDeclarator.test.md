# `harness.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/compiler/lint/rules/harness.test.ts --update-snapshots` to update.

## `js/useSingleVarDeclarator`

### `0`

```

 lint/js/useSingleVarDeclarator/reject/1/file.ts:1 lint/js/useSingleVarDeclarator  FIXABLE  ━━━━━━━━

  ✖ Declare variables separately.

    let foo, bar;
    ^^^^^^^^^^^^^

  ℹ Safe fix

    1   │ - let·foo,·bar;
      1 │ + let·foo;
      2 │ + let·bar;

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `0: formatted`

```ts
let foo;
let bar;

```

### `1`

```
✔ No known problems!

```

### `1: formatted`

```ts
for (let i = 0, x = 1; i < arr.length; i++) {}

```
