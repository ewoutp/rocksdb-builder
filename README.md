# Rocksdb-Builder 

Docker container used to build and test RocksDB.

## Build 

```
docker build -t rocksdb-builder .
```

## Usage 

```
docker run -it --rm -v $(pwd):/usr/code -w /usr/code rocksdb-builder /bin/bash
```
