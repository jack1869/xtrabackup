# xtrabackup

Percona XtraBackup - Documentation
Percona XtraBackup is an open-source hot backup utility for MySQL - based servers that doesn’t lock your database during the backup.

It can back up data from InnoDB, XtraDB, and MyISAM tables on MySQL 5.1 [1], 5.5, 5.6 and 5.7 servers, as well as Percona Server with XtraDB. For a high-level overview of many of its advanced features, including a feature comparison, please see About Percona XtraBackup.

Whether it is a 24x7 highly loaded server or a low-transaction-volume environment, Percona XtraBackup is designed to make backups a seamless procedure without disrupting the performance of the server in a production environment. Commercial support contracts are available.


Percona XtraBackup can back up data from InnoDB, XtraDB, MyISAM, and MyRocks tables on MySQL 8.0 servers as well as Percona Server for MySQL with XtraDB, Percona Server for MySQL 8.0, and Percona XtraDB Cluster 8.0.

Important

The support of the MyRocks storage engine was added in version 8.0.6.

Percona XtraBackup 8.0 does not support the TokuDB storage engine.

See also

Percona TokuBackup
https://www.percona.com/doc/percona-server/LATEST/tokudb/toku_backup.html
Percona XtraBackup 8.0 does not support making backups of databases created in versions prior to 8.0 of MySQL, Percona Server for MySQL or Percona XtraDB Cluster. As the changes that MySQL 8.0 introduced in data dictionaries, redo log and undo log are incompatible with previous versions, it is currently impossible for Percona XtraBackup 8.0 to also support versions prior to 8.0.

For a high-level overview of many of its advanced features, including a feature comparison, please see About Percona XtraBackup.
