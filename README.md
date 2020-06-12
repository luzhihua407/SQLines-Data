# SQLines-Data
SQLines Data 是一款开源(Apache License 2.0)，可伸缩的，并行高性能的data传输、schema转换工具，可以用作数据库迁移和ETL处理。<br>

支持数据库:<br>
Oracle and Oracle Exadata<br>
Microsoft SQL Server and Microsoft Azure SQL<br>
MySQL<br>
MariaDB<br>
PostgreSQL<br>
Amazon Redshift, Amazon Aurora, Amazon RDS and Amazon Athena<br>
IBM DB2 LUW, iSeries (AS/400) and zSeries (S/390)<br>
Sybase Adaptive Server Enterprise, Sybase SQL Anywhere, Sybase IQ and Sybase Advantage<br>
Informix<br>
Teradata<br>
Netezza<br>
Greenplum<br>
Vertica<br>
SAP HANA<br>

SQLines Data是用C/C++语言编写，并且使用原生低级内存中的批量加载器API传输数据，可用在Linux, Windows, both 64-bit and 32-bit 平台。<br>
可以用在跨平台的数据库迁移，包括表的定义、约束、索引和数据。<br>

迁移功能：<br>
1、创建schema，传输数据，创建约束和索引，建立灵活的迁移过程<br>
2、UI和命令行接口<br>

ETL<br>
可以在ETL流程中将SQLines Data作为一款数据extact-load工具。<br>

ETL 功能:<br>
1、并行高性能将数据传输到目标数据库<br>
2、并行高性能导出flat文件，支持压缩的S3或HDFS<br>
3、选择列传输<br>
4、定义SELECT表达式，包括计算列。<br>
5、定义表的WHERE条件以进行增量传输<br>
6、定义SQL SELECT查询以传输数据<br>
7、命令行接口<br>
