Fluentbit playground
====================

Create some logs
----------------
```
git clone git@github.com:sztanyoo/Fake-Apache-Log-Generator.git
docker build -t apache-fake-log-gen .
docker run --rm apache-fake-log-gen -n 10 > my.log
```

Publish logs to Elastic
-----------------------

```
./run.sh
```