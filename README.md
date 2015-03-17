# binarydefer

**Note: not supported anymore**

This library provides a framework for doing binary serialisation, with support for deferred loading. If you don't intend to use the deferred loading side, I recommend the new binary module from Hac 07, as it is pure and likely to be faster for you. If you do need deferred loading, then this is the only module for you!

Deferred loading is for when a large data structure exists, but typically only a small fraction of this data structure will be required. By using deferred loading, some of the data structure can be read quickly, and the rest can be read on demand.
