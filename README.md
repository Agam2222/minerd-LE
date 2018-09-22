# Bitcoin LE CPU miner
CPU miner adapted to LE technology. It supports stratum and can be used in pool mining.

Run ```minerd --help``` to list all options.

Example of pool mining:
```
minerd --url=stratum+tcp://[domain]:[port] -u [wallet] -p x --algo=sha256d -t [threads]
```

Download latest release from [here](../../releases).
