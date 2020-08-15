# [ ](#)管理命令

[]()

> **注意**
>
> 有关特定命令的详细信息，包括语法和示例，请单击特定命令以转到其参考页面。

| 名称                                 | 描述                                                         |
| ------------------------------------ | ------------------------------------------------------------ |
| [`clean`]()                          | 内部名称空间管理命令。                                       |
| [`cloneCollection`]()                | 将集合从远程主机复制到当前主机。                             |
| [`cloneCollectionAsCapped`]()        | 将未设置上限的集合复制为新的设置上限的集合。                 |
| [`collMod`]()                        | 向集合添加选项或修改视图定义。                               |
| [`compact`]()                        | 对集合进行分片整理并重建索引。                               |
| [`connPoolSync`]()                   | 用于刷新连接池的内部命令。                                   |
| [`convertToCapped`]()                | 将无上限的集合转换为有上限的集合。                           |
| [`create`]()                         | 创建一个集合或视图。                                         |
| [`createIndexes`]()                  | 为一个集合构建一个或多个索引。                               |
| [`currentOp`]()                      | 返回一个文档，该文档包含有关数据库实例正在进行的操作的信息。 |
| [`drop`]()                           | 从数据库中删除指定的集合。                                   |
| [`dropDatabase`]()                   | 删除当前数据库。                                             |
| [`dropConnections`]()                | 将外向连接删除到指定的主机列表。                             |
| [`dropIndexes`]()                    | 从集合中删除索引。                                           |
| [`filemd5`]()                        | 返回使用GridFS存储的文件的md5哈希值。                        |
| [`fsync`]()                          | 将挂起的写入刷新到存储层，并锁定数据库以允许备份。           |
| [`fsyncUnlock`]()                    | 解锁一个fsync锁。                                            |
| [`getParameter`]()                   | 检索配置选项。                                               |
| [`killCursors`]()                    | 杀死集合的指定游标。                                         |
| [`killOp`]()                         | 终止操作ID指定的操作。                                       |
| [`listCollections`]()                | 返回当前数据库中的集合列表。                                 |
| [`listDatabases`]()                  | 返回列出所有数据库的文档，并返回基本数据库统计信息。         |
| [`listIndexes`]()                    | 列出集合的所有索引。                                         |
| [`logRotate`]()                      | 循环MongoDB日志，以防止单个文件占用过多空间。                |
| [`reIndex`]()                        | 重建集合上的所有索引。                                       |
| [`renameCollection`]()               | 更改现有集合的名称。                                         |
| [`setFeatureCompatibilityVersion`]() | 启用或禁用保留向后不兼容的数据的功能。                       |
| [`setParameter`]()                   | 修改配置选项。                                               |
| [`shutdown`]()                       | 关闭`mongod`或`mongos`进程。                                 |