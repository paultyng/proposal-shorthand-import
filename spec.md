# Specification

## Imports

### Syntax

*ImportDeclaration* `:`
- `import` *ImportedDefaultBinding* `;`

#### Static Semantics: BoundNames

*ImportDeclaration* `:` `import` *ImportedDefaultBinding* `;`

1. Return the BoundNames of *ImportedDefaultBinding*.

#### Static Semantics: ImportEntries

*ImportDeclaration* `:` `import` *ImportedDefaultBinding* `;`

1. Let *module* be the sole element of ModuleRequests of *ImportedDefaultBinding*.
2. Return ImportEntriesForModule of *ImportedDefaultBinding* with argument *module*.

#### Static Semantics: ModuleRequests

*ImportDeclaration* `:` `import` *ImportedDefaultBinding* `;`

1. Return a List containing the StringValue of *ImportedDefaultBinding*.
