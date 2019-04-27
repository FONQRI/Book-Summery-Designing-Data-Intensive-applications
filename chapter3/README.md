# Storage and Retrieval
* In memory databases write data on disk for log first but index data in memory and they have priority queues and sets
* On disk databases use os hard cash on memory (don't need to read from disk necessarily)
* In-memory databases can support datasets larger than memory by anti-cashing that write least recently used data to disk ( virtual memory and swap)
* In most of analyze queries we need some field of row in table not all of theme this is why column oriented databases exists
* Casaandra and bigtable have column families , they store all column of row together,along with a row key but don't do column compression thus bigtable model are still mostly row oriented
