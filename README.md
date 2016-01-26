# Import Shorthand Syntax
ES7 Proposal, specs, and reference implementation for Import Shorthand Syntax

Spec drafted by [@paultyng](https://github.com/paultyng).

This proposal is currently seeking [stage 0](https://github.com/tc39/ecma262) of the [process](https://tc39.github.io/process-document/).

## Rationale
To simplify usage of `import` when the module specifier and binding identifier are the same.

For example:

```js
import fs from 'fs';
```

Would simply be:

```js
import fs;
```

Similar to object literal shorthand syntax.

## Spec
You can view the spec in [markdown format](spec.md).
