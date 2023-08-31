### MCA examples (requires `JRE`)

#### Usage
```bash
mca <type> <path|name> [[max_memory]|[min_memory] [max_memory]]
```

#### Running spigot server with 2048 megabytes max memory
```bash
mca bukkit ./spigot.jar 2048M
```

#### Running paper server with Aikar flags
```bash
mca bukkit ./paper.jar 2048M
```

#### Running velocity server with Aikar flags
```bash
mca velocity ./velocity.jar 512M 2048M
```

### Paper-DL examples (requires `jq` and `wget`)
#### Download paper jar 1.20.1 latest build (with sha256 checking)
```bash
papermc-dl paper 1.20.1
```

#### Download paper jar 1.12.2 specific build
```bash
papermc-dl paper 1.12.2 1205
```

#### Download velocity jar 3.1.2-SNAPSHOT latest build and force skip sha256 checking
```bash
FORCE=1 papermc-dl velocity 3.1.2-SNAPSHOT
```

