<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [types](./types.md) &gt; [OmitStrict](./types.omitstrict.md)

## OmitStrict type

Similar to the builtin Omit, but checks the filter strictly.

<b>Signature:</b>

```typescript
declare type StrictOmit<T, K extends keyof T> = Pick<T, Exclude<keyof T, K>>;
```