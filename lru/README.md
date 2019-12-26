# groupcache-annotated

### lru
每个K-V都是通过一条LRU链表来管理.经常被访问的数据会被放置在LRU链表的前端,
久而久之冷数据会下沉到链表尾端,甚至直接被移出链表
![Lru image](../doc/images/lru.png)

    