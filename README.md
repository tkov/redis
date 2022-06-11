# REDIS

Hashes
- a hash is a collection of key-value pairs
- redis hashes are maps between string fields and string values

	HSET test demo1 "example1" demo2 "example2"
	OK
	HGET test demo1 
	"example1"
	HGET test demo2
	"example2"

Lists
- lists are simple lists of strings
- they are sorted by insertion order (FIFO)


	lpush myList redis
	(integer) 1
	lpush myList mongodb
	(integer) 2
	lpush myList rabitmq
	(integer) 3
	lrange myList 0 10

	1) "rabitmq"
	2) "mongodb"
	3) "redis"


Sets

-
