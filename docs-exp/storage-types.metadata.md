<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/storage-types](./storage-types.md) &gt; [Metadata](./storage-types.metadata.md)

## Metadata interface

The full set of object metadata, including read-only properties.

<b>Signature:</b>

```typescript
export interface Metadata 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [bucket](./storage-types.metadata.bucket.md) | string | The bucket this object is contained in. |
|  [cacheControl](./storage-types.metadata.cachecontrol.md) | string \| undefined | Served as the 'Cache-Control' header on object download. |
|  [contentDisposition](./storage-types.metadata.contentdisposition.md) | string \| undefined | Served as the 'Content-Disposition' header on object download. |
|  [contentEncoding](./storage-types.metadata.contentencoding.md) | string \| undefined | Served as the 'Content-Encoding' header on object download. |
|  [contentLanguage](./storage-types.metadata.contentlanguage.md) | string \| undefined | Served as the 'Content-Language' header on object download. |
|  [contentType](./storage-types.metadata.contenttype.md) | string \| undefined | Served as the 'Content-Type' header on object download. |
|  [customMetadata](./storage-types.metadata.custommetadata.md) | \| { \[key: string\]: string; } \| undefined | Additional user-defined custom metadata. |
|  [downloadTokens](./storage-types.metadata.downloadtokens.md) | string\[\] \| undefined | Tokens to allow access to the downloatd URL. |
|  [fullPath](./storage-types.metadata.fullpath.md) | string | The full path of this object. |
|  [generation](./storage-types.metadata.generation.md) | string | The object's generation. [https://cloud.google.com/storage/docs/generations-preconditions](https://cloud.google.com/storage/docs/generations-preconditions) |
|  [md5Hash](./storage-types.metadata.md5hash.md) | string \| undefined | A Base64-encoded MD5 hash of the object being uploaded. |
|  [metageneration](./storage-types.metadata.metageneration.md) | string | The object's metageneration. [https://cloud.google.com/storage/docs/generations-preconditions](https://cloud.google.com/storage/docs/generations-preconditions) |
|  [name](./storage-types.metadata.name.md) | string | The short name of this object, which is the last component of the full path. For example, if fullPath is 'full/path/image.png', name is 'image.png'. |
|  [ref](./storage-types.metadata.ref.md) | [StorageReference](./storage-types.storagereference.md) \| undefined | <code>StorageReference</code> associated with this upload. |
|  [size](./storage-types.metadata.size.md) | number | The size of this object, in bytes. |
|  [timeCreated](./storage-types.metadata.timecreated.md) | string | A date string representing when this object was created. |
|  [updated](./storage-types.metadata.updated.md) | string | A date string representing when this object was last updated. |

