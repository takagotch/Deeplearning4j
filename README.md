### deeplearning4j
---
https://github.com/eclipse/deeplearning4j

https://deeplearning4j.org/

```
```

```sh
./change-cuda-versions.sh x.x
mvn clean install -Dmaven.test.skip -Dlibnd4j.cuda=x.x -Dlibnd4j.compute=xx
mvn -B -V -U clean install -pl '!jumpy,!pydatavec,!pydl4j' -Dlibnd4j.platform=linux-x86_64 -Dlibnd4j.chip=cuda -Dlibxxx
```

```
```


