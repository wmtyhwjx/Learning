# 这是手机APP数据的hive代码

## 文件说明
|文件名|说明|
|---|---|
|00_Recreate_db.hql|删除mobile数据库并重建，用于重复导入数据操作|
|01_Import.hql|在mobile数据库下建立表并导入APP使用数据和APP类别数据|
|02_Description.hql|描述统计分析，实现《大数据挖掘与统计机器学习》P198图10.1和10.2的数据|