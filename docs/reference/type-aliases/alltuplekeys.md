---
id: AllTupleKeys
title: AllTupleKeys
---

<!-- DO NOT EDIT: this page is autogenerated from the type comments -->

# Type Alias: AllTupleKeys\<T\>

```ts
type AllTupleKeys<T> = T extends any ? keyof T & `${number}` : never;
```

Defined in: [packages/form-core/src/util-types.ts:64](https://github.com/TanStack/form/blob/main/packages/form-core/src/util-types.ts#L64)

## Type Parameters

• **T**
