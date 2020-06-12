# SQLines-Data
SQLines Data 是一款开源(Apache License 2.0)，可伸缩的，并行高性能的data传输、schema转换工具，可以用作数据库迁移和ETL处理。

支持数据库:
Oracle and Oracle Exadata
Microsoft SQL Server and Microsoft Azure SQL
MySQL
MariaDB
PostgreSQL
Amazon Redshift, Amazon Aurora, Amazon RDS and Amazon Athena
IBM DB2 LUW, iSeries (AS/400) and zSeries (S/390)
Sybase Adaptive Server Enterprise, Sybase SQL Anywhere, Sybase IQ and Sybase Advantage
Informix
Teradata
Netezza
Greenplum
Vertica
SAP HANA

SQLines Data是用C/C++语言编写，并且使用原生低级内存中的批量加载器API传输数据，可用在Linux, Windows, both 64-bit and 32-bit 平台。
可以用在跨平台的数据库迁移，包括表的定义、约束、索引和数据。

迁移功能：
1、创建schema，传输数据，创建约束和索引，建立灵活的迁移过程
2、UI和命令行接口

ETL
可以在ETL流程中将SQLines Data作为一款数据extact-load工具。

ETL 功能:
1、并行高性能将数据传输到目标数据库
2、并行高性能导出flat文件，支持压缩的S3或HDFS
3、选择列传输
4、定义SELECT表达式，包括计算列。
5、定义表的WHERE条件以进行增量传输
6、定义SQL SELECT查询以传输数据
7、命令行接口
