# Simple key-value datastore (redis clone)

## Supported types
* int
* string
* list

### Supported commands
* get key
* set key val
* increment key
* exists key
* delete key
* type key
* expire key ttl
* setexp key val ttl
* ttl key
* lpush key ...values
* rpush key ...values

Server runs on localhost:6379 and saves data to /tmp/kvdata
