#fsmon

文件监控服务。

用于对指定的多个目录进行文件变化检测，用于发现异常的文件操作。将可疑情况报告给管理员。

该服务主要做的是，监控文件的写入频率，超过指定频率则触发报警，认为出现了可疑操作。
