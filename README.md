# docker-node-oracle

Docker image to be used for building a container ready with Oracle instant client binaries and all necessary environment variables needed to use the primary Node.js Oracle Database driver libraries:

[node-oracledb](https://github.com/oracle/node-oracledb)


## Usage

Within your Dockerfile:

```
FROM salvadohrg/node-oracle:{nodeVersion}-{oracleVersion}
```

Updated to use Node 12.10 official container
