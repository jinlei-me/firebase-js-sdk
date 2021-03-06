<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/firestore](./firestore.md) &gt; [/](./firestore_.md) &gt; [SnapshotOptions](./firestore_.snapshotoptions.md) &gt; [serverTimestamps](./firestore_.snapshotoptions.servertimestamps.md)

## SnapshotOptions.serverTimestamps property

If set, controls the return value for server timestamps that have not yet been set to their final value.

By specifying 'estimate', pending server timestamps return an estimate based on the local clock. This estimate will differ from the final value and cause these values to change once the server result becomes available.

By specifying 'previous', pending timestamps will be ignored and return their previous value instead.

If omitted or set to 'none', `null` will be returned by default until the server value becomes available.

<b>Signature:</b>

```typescript
readonly serverTimestamps?: 'estimate' | 'previous' | 'none';
```
