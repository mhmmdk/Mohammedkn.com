---
title: indexdb cheatsheat
description: Usage and reference for indexeddb cheatsheat
---

<table>
  <tr>
    <th>Interface</th>
    <th>Parent</th>
    <th>Implemented by</th>
    <th>Property</th>
    <th>Method</th>
    <th>Event</th>
  </tr>
  <tr>
    <td>IDBEnvironment</td>
    <td></td>
    <td>window, worker</td>
    <td>IDBEnvironment.indexedDB</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>IDBFactory</td>
    <td></td>
    <td>window.indexedDB</td>
    <td></td>
    <td>IDBFactory.open, IDBFactory.deleteDatabase, IDBFactory.cmp</td>
    <td></td>
  </tr>
  <tr>
    <td>IDBOpenDBRequest</td>
    <td>IDBRequest, EventTarget.</td>
    <td></td>
    <td></td>
    <td></td>
    <td>blocked, upgradeneeded</td>
  </tr>
  <tr>
    <td>IDBDatabase</td>
    <td></td>
    <td></td>
    <td>IDBDatabase.name, IDBDatabase.version, IDBDatabase.objectStoreNames</td>
    <td>IDBDatabase.close(), IDBDatabase.createObjectStore(), IDBDatabase.deleteObjectStore(), IDBDatabase.transaction(), </td>
    <td>abort, close, error, versionchange</td>
  </tr>  
  <tr>
    <td>IDBTransaction</td>
    <td>'IDBDatabase.transaction(<array_object_store>, <[readwrite][versionchange][readonly]> )'</td>
    <td></td>
    <td>IDBTransaction.db, IDBTransaction.error, IDBTransaction.mode, IDBTransaction.objectStoreNames </td>
    <td>IDBTransaction.abort, IDBTransaction.objectStore</td>
    <td>abort, complete, error</td>
  </tr>
    <tr>
    <td>IDBRequest</td>
    <td>EventTarget, all</td>
    <td></td>
    <td>IDBRequest.error, IDBRequest.result, IDBRequest.source, IDBRequest.readyState, IDBRequest.transaction</td>
    <td></td>
    <td>error, success</td>
  </tr>
    <tr>
    <td>IDBObjectStore</td>
    <td></td>
    <td></td>
    <td>IDBObjectStore.indexNames, IDBObjectStore.keyPath, IDBObjectStore.name, IDBObjectStore.transaction, IDBObjectStore.autoIncrement</td>
    <td>"IDBObjectStore.add(<val>, <[key]>), IDBObjectStore.clear(), IDBObjectStore.count(<[key|IDBKeyRange]>), IDBObjectStore.createIndex(indexname, indexname, {keyPath: <colum>, <[IDBIndexParameter]>}), IDBObjectStore.delete(<key|keyRange>), IDBObjectStore.deleteIndex(<indexname>), IDBObjectStore.get(<key>), IDBObjectStore.getKey(<key>), IDBObjectStore.getAll(), IDBObjectStore.getAllKeys(), IDBObjectStore.index(<indexname>), IDBObjectStore.openCursor(), IDBObjectStore.openKeyCursor(), IDBObjectStore.put(<item>, <[key]>)"</td>
    <td></td>
  </tr>
    <tr>
    <td>IDBIndex</td>
    <td></td>
    <td></td>
    <td>IDBIndex.name, IDBIndex.objectStore, IDBIndex.keyPath, IDBIndex.multiEntry, IDBIndex.unique</td>
    <td>IDBIndex.count(), IDBIndex.get(), IDBIndex.getKey(), IDBIndex.getAll(), IDBIndex.getAllKeys()IDBIndex.openCursor(), IDBIndex.openKeyCursor()</td>
    <td></td>
  </tr>
    <tr>
    <td>IDBCursor</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
    <tr>
    <td>IDBCursorWithValue</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
    <tr>
    <td>IDBKeyRange</td>
    <td></td>
    <td></td>
    <td>lower, lowerOpen, upper, upperOpen</td>
    <td>bound(), includes(), lowerBound(), only(), upperBound()</td>
    <td>complete, abort, success, error, close</td>
  </tr>
    <tr>
    <td>IDBVersionChangeEvent</td>
    <td></td>
    <td></td>
    <td>newVersion, oldVersion, version</td>
    <td></td>
    <td>complete, abort, success, error, close</td>
</table>
