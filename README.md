# fio-gcp

### Throughput or Bandwidth test 

```
fio throughput.fio
```

### IOPS test

```
fio iops.fio 
```
### Latency test

```
fio latency.fio
```

### Database workload specific testing

#### OLTP : Small Random I/O
rw=randrw
bs=1K


#### OLAP : Large Sequential I/O

rw=read
bs=1M





