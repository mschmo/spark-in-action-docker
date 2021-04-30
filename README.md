# Spark In Action Docker Image

This is a Docker image bundled with everything you need to run the examples from [Spark in Action](https://www.manning.com/books/spark-in-action-second-edition) (2nd Edition).

Build:
```
$ docker build -t spark-in-action .
```

Run the example from Chapter 1:
```
$ docker run -it spark-in-action mvn exec:exec
[INFO] Scanning for projects...
[INFO]
[INFO] --------------< net.jgp.books:spark-in-action2-chapter01 >--------------
[INFO] Building spark-in-action2-chapter01 1.0.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO]
[INFO] --- exec-maven-plugin:1.6.0:exec (default-cli) @ spark-in-action2-chapter01 ---
+---+--------+--------------------+-----------+--------------------+
| id|authorId|               title|releaseDate|                link|
+---+--------+--------------------+-----------+--------------------+
|  1|       1|Fantastic Beasts ...|   11/18/16|http://amzn.to/2k...|
|  2|       1|Harry Potter and ...|    10/6/15|http://amzn.to/2l...|
|  3|       1|The Tales of Beed...|    12/4/08|http://amzn.to/2k...|
|  4|       1|Harry Potter and ...|    10/4/16|http://amzn.to/2k...|
|  5|       2|Informix 12.10 on...|    4/23/17|http://amzn.to/2i...|
+---+--------+--------------------+-----------+--------------------+
only showing top 5 rows

[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  6.369 s
[INFO] Finished at: 2021-04-30T08:58:34Z
[INFO] ------------------------------------------------------------------------
```

Chapter Checklist:
- [X] Ch01
- [ ] Ch02
- [ ] Ch03
- [ ] Ch04
- [ ] Ch05
- [ ] Ch07
- [ ] Ch08
- [ ] Ch09
- [ ] Ch10
- [ ] Ch11
- [ ] Ch12
- [ ] Ch13
- [ ] Ch14
- [ ] Ch15
- [ ] Ch16
- [ ] Ch17