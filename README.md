# c-hashtable

Implementation of a generic hashtable in C (using void* pointers), has pretty much everything you need (uses a linkedlist for buckets instead of a binary tree for simplicity's sake). Also, it doesn't currently support using a custom free function to deallocate the bucket entries, but can be done easily with a function pointer (e.g: '*(free_fun)(hashkey key, hashvalue value) where both hashkey and hashvalue are type aliases for void *
