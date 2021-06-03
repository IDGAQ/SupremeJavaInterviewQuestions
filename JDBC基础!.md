## JDBC面试题!
---

__1. Transaction的ACID是什么?__ <br>
```
&emsp;a. Atomicity 整个事务的原子性 (事务要么全发生了，要么一个都没发生，这整个过程就像原子一样，不可切割)
&emsp;b. Consistency 数据库的一致性(事务发生前，和事务放生后，数据库的)<br>
&emsp;c. Isolation 多个事务的隔离性(多个事务并发时，事务之间是隔离的)<br>
&emsp;d. Durability 数据改变后的耐久性（事务完成后，数据就被永久保留在了数据库，不能被回滚)<br>
```

__2. 数据库三大范式是什么？__
