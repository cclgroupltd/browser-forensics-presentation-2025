# browser-forensics-presentation-2025
Links and resources relating to browser forensics presentation 2025.

# Resources
## Scripts and tools
| Desription | URL |
| ---------- | --- |
| Chromium Profile View (tool for viewing data stored in a Chrome/Chromium) | [https://github.com/cclgroupltd/chrome-profile-view](https://github.com/cclgroupltd/chrome-profile-view) |
| Mister Skinnylegs (plugin framework and tool for processing website/web app artefacts in Chrom(e\|ium) and Firefox | [https://github.com/cclgroupltd/mister-skinnylegs/](https://github.com/cclgroupltd/mister-skinnylegs/) |
| CCL's Python library for LevelDb, IndexedDB, WebStorage, etc., in Chrome/Chromium | [https://github.com/cclgroupltd/ccl_chrome_indexeddb](https://github.com/cclgroupltd/ccl_chromium_reader) |
| CCL's Python library for LevelDb, IndexedDB, WebStorage, etc., in Firefox | [https://github.com/cclgroupltd/ccl_mozilla_reader](https://github.com/cclgroupltd/ccl_mozilla_reader) |
| Unfurl | [https://dfir.blog/unfurl](https://dfir.blog/unfurl) |
| Hindsight | [https://github.com/obsidianforensics/hindsight](https://github.com/obsidianforensics/hindsight) |

## LevelDB
| Desription | URL |
| ---------- | --- |
| Blog describing the format | https://www.cclsolutionsgroup.com/post/hang-on-thats-not-sqlite-chrome-electron-and-leveldb
| Official documentation of the format | https://github.com/google/leveldb/blob/master/doc/table_format.md https://github.com/google/leveldb/blob/master/doc/log_format.md |
| Blog detailing another notable leveldb artefact on Android | https://www.cclsolutionsgroup.com/post/fcm-queued-messages-on-android |

## Webstorage
| Desription | URL |
| ---------- | --- |
| WebStorage Specification | https://html.spec.whatwg.org/multipage/webstorage.html#webstorage |
| Blog explaining the formats (Chromium) | https://www.cclsolutionsgroup.com/post/chromium-session-storage-and-local-storage |
| Source code relating to these artefacts (Chromium) | https://source.chromium.org/chromium/chromium/src/+/main:components/services/storage/dom_storage/ |
| Blogs explaining the formats (Firefox) | https://www.cclsolutionsgroup.com/post/local-storage-and-session-storage-in-mozilla-firefox-part-1 https://www.cclsolutionsgroup.com/post/local-storage-and-session-storage-in-mozilla-firefox-part-2 |

## IndexedDB
| Desription | URL |
| ---------- | --- |
| IndexedDB Specification | https://w3c.github.io/IndexedDB/ |
| Blog covering the format in Chromium | https://www.cclsolutionsgroup.com/post/indexeddb-on-chromium |
| Source code links related to the LevelDB database layout | https://github.com/chromium/chromium/blob/master/content/browser/indexed_db/docs/leveldb_coding_scheme.md https://github.com/chromium/chromium/blob/master/content/browser/indexed_db/indexed_db_leveldb_coding.h https://github.com/chromium/chromium/blob/master/content/browser/indexed_db/indexed_db_leveldb_coding.cc |
| Source code links related to the key structure | https://github.com/chromium/chromium/blob/master/content/browser/indexed_db/indexed_db_leveldb_coding.cc |
| Source code links related to the record structure | https://github.com/v8/v8/blob/master/src/objects/value-serializer.cc https://chromium.googlesource.com/chromium/src/third_party/+/master/blink/renderer/bindings/core/v8/serialization/serialization_tag.h https://chromium.googlesource.com/chromium/src/third_party/+/master/blink/renderer/bindings/core/v8/serialization/v8_script_value_deserializer.h | https://chromium.googlesource.com/chromium/src/third_party/+/master/blink/renderer/bindings/core/v8/serialization/v8_script_value_deserializer.cc
| Source code links related to the external data structures | https://github.com/chromium/chromium/blob/master/content/browser/indexed_db/indexed_db_backing_store.cc |
