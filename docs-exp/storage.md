<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/storage](./storage.md)

## storage package

## Functions

|  Function | Description |
|  --- | --- |
|  [deleteObject(ref)](./storage.deleteobject.md) | Deletes the object at this location. |
|  [getDownloadURL(ref)](./storage.getdownloadurl.md) | Returns the download URL for the given Reference. |
|  [getMetadata(ref)](./storage.getmetadata.md) | A promise that resolves with the metadata for this object. If this object doesn't exist or metadata cannot be retreived, the promise is rejected. |
|  [getStorage(app)](./storage.getstorage.md) | Gets a Firebase StorageService instance for the given Firebase app. |
|  [list(ref, options)](./storage.list.md) | List items (files) and prefixes (folders) under this storage reference.<!-- -->List API is only available for Firebase Rules Version 2.<!-- -->GCS is a key-blob store. Firebase Storage imposes the semantic of '/' delimited folder structure. Refer to GCS's List API if you want to learn more.<!-- -->To adhere to Firebase Rules's Semantics, Firebase Storage does not support objects whose paths end with "/" or contain two consecutive "/"s. Firebase Storage List API will filter these unsupported objects. list() may fail if there are too many unsupported objects in the bucket. |
|  [listAll(ref)](./storage.listall.md) | List all items (files) and prefixes (folders) under this storage reference.<!-- -->This is a helper method for calling list() repeatedly until there are no more results. The default pagination size is 1000.<!-- -->Note: The results may not be consistent if objects are changed while this operation is running.<!-- -->Warning: listAll may potentially consume too many resources if there are too many results. |
|  [ref(storage, url)](./storage.ref.md) | Returns a StorageReference for the given url. |
|  [ref(storageOrRef, path)](./storage.ref_1.md) | Returns a StorageReference for the given path in the default bucket. |
|  [updateMetadata(ref, metadata)](./storage.updatemetadata.md) | Updates the metadata for this object. |
|  [uploadBytes(ref, data, metadata)](./storage.uploadbytes.md) | Uploads data to this object's location. The upload is not resumable. |
|  [uploadBytesResumable(ref, data, metadata)](./storage.uploadbytesresumable.md) | Uploads data to this object's location. The upload can be paused and resumed, and exposes progress updates. |
|  [uploadString(ref, value, format, metadata)](./storage.uploadstring.md) | Uploads a string to this object's location. The upload is not resumable. |

## Variables

|  Variable | Description |
|  --- | --- |
|  [StringFormat](./storage.stringformat.md) | An enumeration of the possible string formats for upload. |

## Type Aliases

|  Type Alias | Description |
|  --- | --- |
|  [StringFormat](./storage.stringformat.md) | An enumeration of the possible string formats for upload. |

