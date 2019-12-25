- Show all node available:

```
root@platform-zzz-aerospike-9:~# docker node ls
ID                            HOSTNAME                          STATUS              AVAILABILITY        MANAGER STATUS      ENGINE VERSION
adasdadqwr2 *      platform-zzz-aerospike-9.20   Ready               Active              Reachable           19.03.1
24124124123423     platform-zzz-aerospike-9.21   Ready               Active              Reachable           19.03.1
wqeq34234234       platform-asd-aerospike-9.22   Ready               Active              Leader              19.03.1
sdfset32t43t4wef   platform-zzz-aerospike-9.23   Ready               Active                                  19.03.1
q35qwrfqwqw        platform-zzz-aerospike-9.24   Ready               Active                                  19.03.1
23523rqfqffqwfwef  platform-zzz-aerospike-9.25   Ready               Active                                  19.03.1
```

- Show all stack available
```
root@asd-group-aerospike-9:/data/softs/aerospike-docker-swarm# docker stack ls
NAME                SERVICES            ORCHESTRATOR
aer-cluster-6000    1                   Swarm
aer-cluster-7000    1                   Swarm
aer-cluster-8000    1                   Swarm
aer-cluster-9000    1                   Swarm
aer-cluster-11000   1                   Swarm
aer-cluster-12000   1                   Swarm
aer-cluster-13000   1                   Swarm
aer-cluster-14000   1                   Swarm
aer-cluster-15000   1                   Swarm
aes-cluster-5000    1                   Swarm
as-cluster-4000     1                   Swarm
```

- Some commands

```
 docker stack ls
 docker stack rm aer-cluster-7000
 docker stack deploy -c aerospike.yml aer-cluster-7000
 ```
 
 
