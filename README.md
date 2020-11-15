# Golang programs from scratch

## Web Framework - GemWeb

[Gee](https://geektutu.com/post/gee.html) is a [gin](https://github.com/gin-gonic/gin)-like framework

- http.Handler Interface Basic [Code](gee-web/day1-http-base)
- Design a Flexiable Context [Code](gee-web/day2-context)
- Router with Trie-Tree Algorithm [Code](gee-web/day3-router)
- Group Control [Code](gee-web/day4-group)
- Middleware Mechanism [Code](gee-web/day5-middleware)
- Embeded Template Support [Code](gee-web/day6-template)
- Panic Recover & Make it Robust [Code](gee-web/day7-panic-recover)

## Distributed Cache - GemCache

[GeeCache](https://geektutu.com/post/geecache.html) is a [groupcache](https://github.com/golang/groupcache)-like distributed cache

- LRU (Least Recently Used) Caching Strategy [Code](gee-cache/day1-lru)
- Single Machine Concurrent Cache [Code](gee-cache/day2-single-node)
- Launch a HTTP Server [Code](gee-cache/day3-http-server)
- Consistent Hash Algorithm [Code](gee-cache/day4-consistent-hash)
- Communication between Distributed Nodes [Code](gee-cache/day5-multi-nodes)
- Cache Breakdown & Single Flight  | [Code](gee-cache/day6-single-flight)
- Use Protobuf as RPC Data Exchange Type | [Code](gee-cache/day7-proto-buf)

## Object Relational Mapping - GemORM

[GeeORM](https://geektutu.com/post/geeorm.html) is a [gorm](https://github.com/jinzhu/gorm)-like and [xorm](https://github.com/go-xorm/xorm)-like object relational mapping library

Xorm's desgin is easier to understand than gorm-v1, so the main designs references xorm and some detailed implementions references gorm-v1.

- Database/sql Basic | [Code](gee-orm/day1-database-sql)
- Object Schame Mapping | [Code](gee-orm/day2-reflect-schema)
- Insert and Query | [Code](gee-orm/day3-save-query)
- Chain, Delete and Update | [Code](gee-orm/day4-chain-operation)
- Support Hooks | [Code](gee-orm/day5-hooks)
- Support Transaction | [Code](gee-orm/day6-transaction)
- Migrate Database | [Code](gee-orm/day7-migrate)

## RPC Framework - GemRPC

[GeeRPC](https://geektutu.com/post/geerpc.html) is a [net/rpc](https://github.com/golang/go/tree/master/src/net/rpc)-like RPC framework

Based on golang standard library `net/rpc`, GeeRPC implements more features. eg, protocol exchange, service registration and discovery, load balance, etc.

- Server Message Codec | [Code](gee-rpc/day1-codec)
- Concurrent Client | [Code](gee-rpc/day2-client)
- Service Register | [Code](gee-rpc/day3-service )
- Timeout Processing | [Code](gee-rpc/day4-timeout )
- Support HTTP Protocol | [Code](gee-rpc/day5-http-debug)
- Load Balance | [Code](gee-rpc/day6-load-balance)
- Discovery and Registry | [Code](gee-rpc/day7-registry)
