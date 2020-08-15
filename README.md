# flink-examples
Flink examples, adopt from: https://github.com/apache/flink/tree/master/flink-examples

Build jar in command line:
``` text
$ mvn package -X
......
[INFO] ------------------------------------------------------------------------
[INFO] Reactor Summary:
[INFO]
[INFO] Flink : Examples : ................................. SUCCESS [  0.434 s]
[INFO] Flink : Examples : Batch ........................... SUCCESS [ 17.478 s]
[INFO] Flink : Examples : Streaming ....................... SUCCESS [ 16.591 s]
[INFO] Flink : Examples : Table ........................... SUCCESS [  9.540 s]
[INFO] Flink : Examples : Build Helper : .................. SUCCESS [  0.005 s]
[INFO] Flink : Examples : Build Helper : Streaming Twitter  SUCCESS [  0.724 s]
[INFO] Flink : Examples : Build Helper : Streaming State machine SUCCESS [  0.619 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 45.521 s
[INFO] ------------------------------------------------------------------------
```

Note: These examples can be run in Intellij IDEA easily.
