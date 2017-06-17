# project1.3

[acadgild@localhost ~]$ jps
2888 Jps
[acadgild@localhost ~]$ start-all.sh
This script is Deprecated. Instead use start-dfs.sh and start-yarn.sh
17/06/17 10:53:08 WARN util.NativeCodeLoader: Unable to load native-hadoop library for your platform... using builtin-java classes where applicable
Starting namenodes on [localhost]
localhost: starting namenode, logging to /usr/local/hadoop-2.6.0/logs/hadoop-acadgild-namenode-localhost.localdomain.out
localhost: starting datanode, logging to /usr/local/hadoop-2.6.0/logs/hadoop-acadgild-datanode-localhost.localdomain.out
Starting secondary namenodes [0.0.0.0]
0.0.0.0: starting secondarynamenode, logging to /usr/local/hadoop-2.6.0/logs/hadoop-acadgild-secondarynamenode-localhost.localdomain.out
17/06/17 10:54:59 WARN util.NativeCodeLoader: Unable to load native-hadoop library for your platform... using builtin-java classes where applicable
starting yarn daemons
starting resourcemanager, logging to /usr/local/hadoop-2.6.0/logs/yarn-acadgild-resourcemanager-localhost.localdomain.out
localhost: starting nodemanager, logging to /usr/local/hadoop-2.6.0/logs/yarn-acadgild-nodemanager-localhost.localdomain.out
[acadgild@localhost ~]$ pig
2017-06-17 10:57:23,739 INFO  [main] pig.ExecTypeProvider: Trying ExecType : LOCAL
2017-06-17 10:57:23,754 INFO  [main] pig.ExecTypeProvider: Trying ExecType : MAPREDUCE
2017-06-17 10:57:23,757 INFO  [main] pig.ExecTypeProvider: Picked MAPREDUCE as the ExecType
2017-06-17 10:57:24,293 [main] INFO  org.apache.pig.Main - Apache Pig version 0.14.0 (r1640057) compiled Nov 16 2014, 18:02:05
2017-06-17 10:57:24,294 [main] INFO  org.apache.pig.Main - Logging error messages to: /home/acadgild/pig_1497677244288.log
2017-06-17 10:57:24,515 [main] INFO  org.apache.pig.impl.util.Utils - Default bootup file /home/acadgild/.pigbootup not found
2017-06-17 10:57:30,735 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.job.tracker is deprecated. Instead, use mapreduce.jobtracker.address
2017-06-17 10:57:30,739 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - fs.default.name is deprecated. Instead, use fs.defaultFS
2017-06-17 10:57:30,739 [main] INFO  org.apache.pig.backend.hadoop.executionengine.HExecutionEngine - Connecting to hadoop file system at: hdfs://localhost:9000
2017-06-17 10:57:30,777 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.used.genericoptionsparser is deprecated. Instead, use mapreduce.client.genericoptionsparser.used
SLF4J: Class path contains multiple SLF4J bindings.
SLF4J: Found binding in [jar:file:/usr/local/hbase/lib/slf4j-log4j12-1.6.4.jar!/org/slf4j/impl/StaticLoggerBinder.class]
SLF4J: Found binding in [jar:file:/usr/local/hadoop-2.6.0/share/hadoop/common/lib/slf4j-log4j12-1.7.5.jar!/org/slf4j/impl/StaticLoggerBinder.class]
SLF4J: See http://www.slf4j.org/codes.html#multiple_bindings for an explanation.
2017-06-17 10:57:34,166 [main] WARN  org.apache.hadoop.util.NativeCodeLoader - Unable to load native-hadoop library for your platform... using builtin-java classes where applicable
2017-06-17 10:57:39,130 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - fs.default.name is deprecated. Instead, use fs.defaultFS
grunt> REGISTER '/home/acadgild/elephant-bird-hadoop-compat-4.1.jar';
2017-06-17 11:00:02,893 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.job.tracker.persist.jobstatus.hours is deprecated. Instead, use mapreduce.jobtracker.persist.jobstatus.hours
2017-06-17 11:00:02,894 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.heartbeats.in.second is deprecated. Instead, use mapreduce.jobtracker.heartbeats.in.second
2017-06-17 11:00:02,894 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - jobclient.completion.poll.interval is deprecated. Instead, use mapreduce.client.completion.pollinterval
2017-06-17 11:00:02,894 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.tasktracker.tasks.sleeptime-before-sigkill is deprecated. Instead, use mapreduce.tasktracker.tasks.sleeptimebeforesigkill
2017-06-17 11:00:02,894 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.job.tracker.http.address is deprecated. Instead, use mapreduce.jobtracker.http.address
2017-06-17 11:00:02,895 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.replication.considerLoad is deprecated. Instead, use dfs.namenode.replication.considerLoad
2017-06-17 11:00:02,895 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.block.size is deprecated. Instead, use dfs.blocksize
2017-06-17 11:00:02,895 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.permissions is deprecated. Instead, use dfs.permissions.enabled
2017-06-17 11:00:02,901 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - topology.node.switch.mapping.impl is deprecated. Instead, use net.topology.node.switch.mapping.impl
2017-06-17 11:00:02,901 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.access.time.precision is deprecated. Instead, use dfs.namenode.accesstime.precision
2017-06-17 11:00:02,901 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.skip.map.max.skip.records is deprecated. Instead, use mapreduce.map.skip.maxrecords
2017-06-17 11:00:02,901 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.submit.replication is deprecated. Instead, use mapreduce.client.submit.file.replication
2017-06-17 11:00:02,901 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.https.client.keystore.resource is deprecated. Instead, use dfs.client.https.keystore.resource
2017-06-17 11:00:02,902 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - job.end.retry.attempts is deprecated. Instead, use mapreduce.job.end-notification.retry.attempts
2017-06-17 11:00:02,904 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.write.packet.size is deprecated. Instead, use dfs.client-write-packet-size
2017-06-17 11:00:02,904 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.reduce.slowstart.completed.maps is deprecated. Instead, use mapreduce.job.reduce.slowstart.completedmaps
2017-06-17 11:00:02,916 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.backup.http.address is deprecated. Instead, use dfs.namenode.backup.http-address
2017-06-17 11:00:02,916 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.task.profile.reduces is deprecated. Instead, use mapreduce.task.profile.reduces
2017-06-17 11:00:02,917 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.job.queue.name is deprecated. Instead, use mapreduce.job.queuename
2017-06-17 11:00:02,917 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.job.tracker.jobhistory.lru.cache.size is deprecated. Instead, use mapreduce.jobtracker.jobhistory.lru.cache.size
2017-06-17 11:00:02,917 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.skip.attempts.to.start.skipping is deprecated. Instead, use mapreduce.task.skip.start.attempts
2017-06-17 11:00:02,917 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.safemode.threshold.pct is deprecated. Instead, use dfs.namenode.safemode.threshold-pct
2017-06-17 11:00:02,917 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.tasktracker.expiry.interval is deprecated. Instead, use mapreduce.jobtracker.expire.trackers.interval
2017-06-17 11:00:02,920 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - keep.failed.task.files is deprecated. Instead, use mapreduce.task.files.preserve.failedtasks
2017-06-17 11:00:02,931 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.tasktracker.map.tasks.maximum is deprecated. Instead, use mapreduce.tasktracker.map.tasks.maximum
2017-06-17 11:00:02,931 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.datanode.max.xcievers is deprecated. Instead, use dfs.datanode.max.transfer.threads
2017-06-17 11:00:02,931 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.max.tracker.failures is deprecated. Instead, use mapreduce.job.maxtaskfailures.per.tracker
2017-06-17 11:00:02,931 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.replication.min is deprecated. Instead, use dfs.namenode.replication.min
2017-06-17 11:00:02,931 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.name.dir is deprecated. Instead, use dfs.namenode.name.dir
2017-06-17 11:00:02,935 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.map.child.log.level is deprecated. Instead, use mapreduce.map.log.level
2017-06-17 11:00:02,935 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.local.dir is deprecated. Instead, use mapreduce.cluster.local.dir
2017-06-17 11:00:02,935 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.child.tmp is deprecated. Instead, use mapreduce.task.tmp.dir
2017-06-17 11:00:02,935 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.local.dir.minspacestart is deprecated. Instead, use mapreduce.tasktracker.local.dir.minspacestart
2017-06-17 11:00:02,936 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - fs.checkpoint.period is deprecated. Instead, use dfs.namenode.checkpoint.period
2017-06-17 11:00:02,938 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.safemode.extension is deprecated. Instead, use dfs.namenode.safemode.extension
2017-06-17 11:00:02,939 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - tasktracker.http.threads is deprecated. Instead, use mapreduce.tasktracker.http.threads
2017-06-17 11:00:02,939 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.map.tasks.speculative.execution is deprecated. Instead, use mapreduce.map.speculative
2017-06-17 11:00:02,939 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.jobtracker.restart.recover is deprecated. Instead, use mapreduce.jobtracker.restart.recover
2017-06-17 11:00:02,939 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.jobtracker.taskScheduler is deprecated. Instead, use mapreduce.jobtracker.taskscheduler
2017-06-17 11:00:02,939 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapreduce.jobtracker.split.metainfo.maxsize is deprecated. Instead, use mapreduce.job.split.metainfo.maxsize
2017-06-17 11:00:02,947 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.task.timeout is deprecated. Instead, use mapreduce.task.timeout
2017-06-17 11:00:02,947 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - hadoop.native.lib is deprecated. Instead, use io.native.lib.available
2017-06-17 11:00:02,947 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.task.tracker.report.address is deprecated. Instead, use mapreduce.tasktracker.report.address
2017-06-17 11:00:02,947 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.secondary.http.address is deprecated. Instead, use dfs.namenode.secondary.http-address
2017-06-17 11:00:02,948 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.data.dir is deprecated. Instead, use dfs.datanode.data.dir
2017-06-17 11:00:02,948 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.task.profile is deprecated. Instead, use mapreduce.task.profile
2017-06-17 11:00:02,948 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.job.reduce.markreset.buffer.percent is deprecated. Instead, use mapreduce.reduce.markreset.buffer.percent
2017-06-17 11:00:02,948 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.merge.recordsBeforeProgress is deprecated. Instead, use mapreduce.task.merge.progress.records
2017-06-17 11:00:02,948 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.job.reduce.input.buffer.percent is deprecated. Instead, use mapreduce.reduce.input.buffer.percent
2017-06-17 11:00:02,948 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.job.shuffle.input.buffer.percent is deprecated. Instead, use mapreduce.reduce.shuffle.input.buffer.percent
2017-06-17 11:00:02,949 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - job.end.retry.interval is deprecated. Instead, use mapreduce.job.end-notification.retry.interval
2017-06-17 11:00:02,949 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.tasktracker.dns.nameserver is deprecated. Instead, use mapreduce.tasktracker.dns.nameserver
2017-06-17 11:00:02,949 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.speculative.execution.slowTaskThreshold is deprecated. Instead, use mapreduce.job.speculative.slowtaskthreshold
2017-06-17 11:00:02,964 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.name.dir.restore is deprecated. Instead, use dfs.namenode.name.dir.restore
2017-06-17 11:00:02,964 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.df.interval is deprecated. Instead, use fs.df.interval
2017-06-17 11:00:02,964 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.temp.dir is deprecated. Instead, use mapreduce.cluster.temp.dir
2017-06-17 11:00:02,964 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.acls.enabled is deprecated. Instead, use mapreduce.cluster.acls.enabled
2017-06-17 11:00:02,964 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - io.sort.spill.percent is deprecated. Instead, use mapreduce.map.sort.spill.percent
2017-06-17 11:00:02,964 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.tasktracker.instrumentation is deprecated. Instead, use mapreduce.tasktracker.instrumentation
2017-06-17 11:00:02,968 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.job.tracker.handler.count is deprecated. Instead, use mapreduce.jobtracker.handler.count
2017-06-17 11:00:02,968 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.reduce.tasks.speculative.execution is deprecated. Instead, use mapreduce.reduce.speculative
2017-06-17 11:00:02,968 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.job.shuffle.merge.percent is deprecated. Instead, use mapreduce.reduce.shuffle.merge.percent
2017-06-17 11:00:02,968 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.committer.job.setup.cleanup.needed is deprecated. Instead, use mapreduce.job.committer.setup.cleanup.needed
2017-06-17 11:00:02,968 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.system.dir is deprecated. Instead, use mapreduce.jobtracker.system.dir
2017-06-17 11:00:02,968 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.job.tracker.retiredjobs.cache.size is deprecated. Instead, use mapreduce.jobtracker.retiredjobs.cache.size
2017-06-17 11:00:02,968 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.jobtracker.instrumentation is deprecated. Instead, use mapreduce.jobtracker.instrumentation
2017-06-17 11:00:02,969 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapreduce.job.counters.limit is deprecated. Instead, use mapreduce.job.counters.max
2017-06-17 11:00:02,969 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.skip.reduce.max.skip.groups is deprecated. Instead, use mapreduce.reduce.skip.maxgroups
2017-06-17 11:00:02,969 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.jobtracker.maxtasks.per.job is deprecated. Instead, use mapreduce.jobtracker.maxtasks.perjob
2017-06-17 11:00:02,974 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.task.tracker.task-controller is deprecated. Instead, use mapreduce.tasktracker.taskcontroller
2017-06-17 11:00:02,974 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.reduce.parallel.copies is deprecated. Instead, use mapreduce.reduce.shuffle.parallelcopies
2017-06-17 11:00:02,974 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - jobclient.progress.monitor.poll.interval is deprecated. Instead, use mapreduce.client.progressmonitor.pollinterval
2017-06-17 11:00:02,975 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.map.max.attempts is deprecated. Instead, use mapreduce.map.maxattempts
2017-06-17 11:00:02,975 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - io.sort.factor is deprecated. Instead, use mapreduce.task.io.sort.factor
2017-06-17 11:00:02,975 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.task.profile.maps is deprecated. Instead, use mapreduce.task.profile.maps
2017-06-17 11:00:02,976 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.shuffle.read.timeout is deprecated. Instead, use mapreduce.reduce.shuffle.read.timeout
2017-06-17 11:00:02,976 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.tasktracker.indexcache.mb is deprecated. Instead, use mapreduce.tasktracker.indexcache.mb
2017-06-17 11:00:02,976 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.max.tracker.blacklists is deprecated. Instead, use mapreduce.jobtracker.tasktracker.maxblacklists
2017-06-17 11:00:02,982 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - io.sort.mb is deprecated. Instead, use mapreduce.task.io.sort.mb
2017-06-17 11:00:02,983 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - topology.script.number.args is deprecated. Instead, use net.topology.script.number.args
2017-06-17 11:00:02,983 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.http.address is deprecated. Instead, use dfs.namenode.http-address
2017-06-17 11:00:02,983 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.permissions.supergroup is deprecated. Instead, use dfs.permissions.superusergroup
2017-06-17 11:00:03,007 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.tasktracker.dns.interface is deprecated. Instead, use mapreduce.tasktracker.dns.interface
2017-06-17 11:00:03,008 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.job.tracker.persist.jobstatus.active is deprecated. Instead, use mapreduce.jobtracker.persist.jobstatus.active
2017-06-17 11:00:03,010 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.compress.map.output is deprecated. Instead, use mapreduce.map.output.compress
2017-06-17 11:00:03,011 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.task.cache.levels is deprecated. Instead, use mapreduce.jobtracker.taskcache.levels
2017-06-17 11:00:03,011 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.min.split.size is deprecated. Instead, use mapreduce.input.fileinputformat.split.minsize
2017-06-17 11:00:03,011 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.output.compress is deprecated. Instead, use mapreduce.output.fileoutputformat.compress
2017-06-17 11:00:03,012 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.https.address is deprecated. Instead, use dfs.namenode.https-address
2017-06-17 11:00:03,012 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.map.tasks is deprecated. Instead, use mapreduce.job.maps
2017-06-17 11:00:03,018 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.speculative.execution.slowNodeThreshold is deprecated. Instead, use mapreduce.job.speculative.slownodethreshold
2017-06-17 11:00:03,019 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.job.tracker.persist.jobstatus.dir is deprecated. Instead, use mapreduce.jobtracker.persist.jobstatus.dir
2017-06-17 11:00:03,019 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.task.tracker.http.address is deprecated. Instead, use mapreduce.tasktracker.http.address
2017-06-17 11:00:03,019 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.tasktracker.taskmemorymanager.monitoring-interval is deprecated. Instead, use mapreduce.tasktracker.taskmemorymanager.monitoringinterval
2017-06-17 11:00:03,019 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.inmem.merge.threshold is deprecated. Instead, use mapreduce.reduce.merge.inmem.threshold
2017-06-17 11:00:03,019 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.umaskmode is deprecated. Instead, use fs.permissions.umask-mode
2017-06-17 11:00:03,019 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.backup.address is deprecated. Instead, use dfs.namenode.backup.address
2017-06-17 11:00:03,024 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.map.output.compression.codec is deprecated. Instead, use mapreduce.map.output.compress.codec
2017-06-17 11:00:03,025 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.reduce.child.log.level is deprecated. Instead, use mapreduce.reduce.log.level
2017-06-17 11:00:03,025 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - fs.checkpoint.edits.dir is deprecated. Instead, use dfs.namenode.checkpoint.edits.dir
2017-06-17 11:00:03,031 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.healthChecker.interval is deprecated. Instead, use mapreduce.tasktracker.healthchecker.interval
2017-06-17 11:00:03,032 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.output.compression.codec is deprecated. Instead, use mapreduce.output.fileoutputformat.compress.codec
2017-06-17 11:00:03,035 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.speculative.execution.speculativeCap is deprecated. Instead, use mapreduce.job.speculative.speculativecap
2017-06-17 11:00:03,036 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - io.bytes.per.checksum is deprecated. Instead, use dfs.bytes-per-checksum
2017-06-17 11:00:03,036 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - fs.checkpoint.dir is deprecated. Instead, use dfs.namenode.checkpoint.dir
2017-06-17 11:00:03,036 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.balance.bandwidthPerSec is deprecated. Instead, use dfs.datanode.balance.bandwidthPerSec
2017-06-17 11:00:03,036 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.shuffle.connect.timeout is deprecated. Instead, use mapreduce.reduce.shuffle.connect.timeout
2017-06-17 11:00:03,036 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.reduce.tasks is deprecated. Instead, use mapreduce.job.reduces
2017-06-17 11:00:03,036 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.https.need.client.auth is deprecated. Instead, use dfs.client.https.need-auth
2017-06-17 11:00:03,037 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - jobclient.output.filter is deprecated. Instead, use mapreduce.client.output.filter
2017-06-17 11:00:03,037 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.jobtracker.job.history.block.size is deprecated. Instead, use mapreduce.jobtracker.jobhistory.block.size
2017-06-17 11:00:03,048 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.output.compression.type is deprecated. Instead, use mapreduce.output.fileoutputformat.compress.type
2017-06-17 11:00:03,048 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.job.reuse.jvm.num.tasks is deprecated. Instead, use mapreduce.job.jvm.numtasks
2017-06-17 11:00:03,049 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.reduce.max.attempts is deprecated. Instead, use mapreduce.reduce.maxattempts
2017-06-17 11:00:03,049 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - fs.default.name is deprecated. Instead, use fs.defaultFS
2017-06-17 11:00:03,049 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.healthChecker.script.timeout is deprecated. Instead, use mapreduce.tasktracker.healthchecker.script.timeout
2017-06-17 11:00:03,051 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.tasktracker.reduce.tasks.maximum is deprecated. Instead, use mapreduce.tasktracker.reduce.tasks.maximum
2017-06-17 11:00:03,051 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.userlog.limit.kb is deprecated. Instead, use mapreduce.task.userlog.limit.kb
2017-06-17 11:00:03,057 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.userlog.retain.hours is deprecated. Instead, use mapreduce.job.userlog.retain.hours
2017-06-17 11:00:03,057 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.max.objects is deprecated. Instead, use dfs.namenode.max.objects
2017-06-17 11:00:03,057 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.name.edits.dir is deprecated. Instead, use dfs.namenode.edits.dir
2017-06-17 11:00:03,058 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - dfs.replication.interval is deprecated. Instead, use dfs.namenode.replication.interval
2017-06-17 11:00:03,058 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapred.local.dir.minspacekill is deprecated. Instead, use mapreduce.tasktracker.local.dir.minspacekill
grunt> REGISTER '/home/acadgild/elephant-bird-hadoop-compat-4.1.jar';
grunt> REGISTER '/home/acadgild/elephant-bird-pig-4.1.jar';
2017-06-17 11:00:34,191 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapreduce.job.counters.limit is deprecated. Instead, use mapreduce.job.counters.max
2017-06-17 11:00:34,214 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - io.bytes.per.checksum is deprecated. Instead, use dfs.bytes-per-checksum
2017-06-17 11:00:34,214 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - fs.default.name is deprecated. Instead, use fs.defaultFS
grunt> REGISTER '/home/acadgild/elephant-bird-pig-4.1.jar';
grunt> REGISTER '/home/acadgild/json-simple-1.1.1.jar';
2017-06-17 11:01:13,979 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapreduce.job.counters.limit is deprecated. Instead, use mapreduce.job.counters.max
2017-06-17 11:01:13,985 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - io.bytes.per.checksum is deprecated. Instead, use dfs.bytes-per-checksum
2017-06-17 11:01:13,986 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - fs.default.name is deprecated. Instead, use fs.defaultFS
grunt> REGISTER '/home/acadgild/json-simple-1.1.1.jar';
grunt> load_tweets = LOAD '/user/flume/tweets/' USING com.twitter.elephantbird.pig.load.JsonLoader('-nestedLoad') AS myMap;
2017-06-17 11:02:26,478 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapreduce.job.counters.limit is deprecated. Instead, use mapreduce.job.counters.max
2017-06-17 11:02:26,483 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - io.bytes.per.checksum is deprecated. Instead, use dfs.bytes-per-checksum
2017-06-17 11:02:26,484 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - fs.default.name is deprecated. Instead, use fs.defaultFS
grunt> load_tweets = LOAD '/user/flume/tweets/' USING com.twitter.elephantbird.pig.load.JsonLoader('-nestedLoad') AS myMap;
2017-06-17 11:22:08,136 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapreduce.job.counters.limit is deprecated. Instead, use mapreduce.job.counters.max
2017-06-17 11:22:08,138 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - io.bytes.per.checksum is deprecated. Instead, use dfs.bytes-per-checksum
2017-06-17 11:22:08,142 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - fs.default.name is deprecated. Instead, use fs.defaultFS
grunt> extract_details = FOREACH load_tweets GENERATE myMap#'id' as id,myMap#'text' as text;
2017-06-17 11:22:41,777 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_MAP 2 time(s).
grunt> tokens = foreach extract_details generate id,text, FLATTEN(TOKENIZE(text)) As word;
2017-06-17 11:23:59,183 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_CHARARRAY 1 time(s).
2017-06-17 11:23:59,184 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_MAP 2 time(s).
2017-06-17 11:23:59,184 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning USING_OVERLOADED_FUNCTION 1 time(s).
grunt> dictionary = load '/AFINN.txt' using PigStorage('\t') AS(word:chararray,rating:int);
2017-06-17 11:24:38,750 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - mapreduce.job.counters.limit is deprecated. Instead, use mapreduce.job.counters.max
2017-06-17 11:24:38,752 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - io.bytes.per.checksum is deprecated. Instead, use dfs.bytes-per-checksum
2017-06-17 11:24:38,757 [main] INFO  org.apache.hadoop.conf.Configuration.deprecation - fs.default.name is deprecated. Instead, use fs.defaultFS
2017-06-17 11:24:38,908 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_CHARARRAY 1 time(s).
2017-06-17 11:24:38,913 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_MAP 2 time(s).
2017-06-17 11:24:38,913 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning USING_OVERLOADED_FUNCTION 1 time(s).
grunt>  
grunt> word_rating = join tokens by word left outer, dictionary by word using 'replicated';
2017-06-17 11:25:16,722 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_CHARARRAY 1 time(s).
2017-06-17 11:25:16,723 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_MAP 2 time(s).
2017-06-17 11:25:16,723 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning USING_OVERLOADED_FUNCTION 1 time(s).
grunt> rating = foreach word_rating generate tokens::id as id,tokens::text as text, dictionary::rating as rate;
2017-06-17 11:25:49,185 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_CHARARRAY 1 time(s).
2017-06-17 11:25:49,186 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_MAP 2 time(s).
2017-06-17 11:25:49,186 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning USING_OVERLOADED_FUNCTION 1 time(s).
grunt> word_group = group rating by (id,text);
2017-06-17 11:26:18,128 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_CHARARRAY 1 time(s).
2017-06-17 11:26:18,128 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_MAP 2 time(s).
2017-06-17 11:26:18,128 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning USING_OVERLOADED_FUNCTION 1 time(s).
grunt> 
grunt> rating = foreach word_rating generate tokens::id as id,tokens::text as text, dictionary::rating as rate;
2017-06-17 11:25:49,185 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_CHARARRAY 1 time(s).
2017-06-17 11:25:49,186 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_MAP 2 time(s).
2017-06-17 11:25:49,186 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning USING_OVERLOADED_FUNCTION 1 time(s).
grunt> word_group = group rating by (id,text);
2017-06-17 11:26:18,128 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_CHARARRAY 1 time(s).
2017-06-17 11:26:18,128 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_MAP 2 time(s).
2017-06-17 11:26:18,128 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning USING_OVERLOADED_FUNCTION 1 time(s).
grunt> avg_rate = foreach word_group generate group, AVG(rating.rate) as tweet_rating;
2017-06-17 11:27:25,462 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_CHARARRAY 1 time(s).
2017-06-17 11:27:25,463 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_MAP 2 time(s).
2017-06-17 11:27:25,463 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning USING_OVERLOADED_FUNCTION 1 time(s).
grunt> positive_tweets = filter avg_rate by tweet_rating>=0;
2017-06-17 11:28:10,073 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_CHARARRAY 1 time(s).
2017-06-17 11:28:10,073 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_DOUBLE 1 time(s).
2017-06-17 11:28:10,073 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning IMPLICIT_CAST_TO_MAP 2 time(s).
2017-06-17 11:28:10,073 [main] WARN  org.apache.pig.newplan.BaseOperatorPlan - Encountered Warning USING_OVERLOADED_FUNCTION 1 time(s).

