---
title: Migrate cancel
series: vtctldclient
commit: d3012c188ea0cfc6837917fc6642ea23be9bb1ff
---
## vtctldclient Migrate cancel

Cancel a Migrate VReplication workflow.

```
vtctldclient Migrate cancel
```

### Examples

```
vtctldclient --server localhost:15999 Migrate --workflow import --target-keyspace customer cancel
```

### Options

```
  -h, --help   help for cancel
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout to use for the command (default 1h0m0s)
      --compact                   use compact format for otherwise verbose outputs
      --format string             The format of the output; supported formats are: text,json. (default "text")
      --server string             server to use for the connection (required)
      --target-keyspace string    Target keyspace for this workflow.
  -w, --workflow string           The workflow you want to perform the command on.
```

### SEE ALSO

* [vtctldclient Migrate](./vtctldclient_migrate/)	 - Migrate is used to import data from an external cluster into the current cluster.

