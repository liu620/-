acid
原子性：undo log
一致性：最和兴和最本质的要就
隔离性：锁，mvcc
持久性：redo log

mvcc multi-version concurrency control
当前读：必须读取到当前数据
快照读：提高数据库的并发查询能力

三个隐式字段（DB_TRX_ID,DB_ROLL_PTR,DB_ROW_ID），undolog，readview
