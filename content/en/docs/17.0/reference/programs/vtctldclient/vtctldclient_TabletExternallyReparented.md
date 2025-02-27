---
title: TabletExternallyReparented
series: vtctldclient
commit: 9a3d0f4a69a840cfa2cb86654abd4afa0be6e0aa
---
## vtctldclient TabletExternallyReparented

Updates the topology record for the tablet's shard to acknowledge that an external tool made this tablet the primary.

### Synopsis

Updates the topology record for the tablet's shard to acknowledge that an external tool made this tablet the primary.

See the Reparenting guide for more information: https://vitess.io/docs/user-guides/configuration-advanced/reparenting/#external-reparenting.


```
vtctldclient TabletExternallyReparented <alias>
```

### Options

```
  -h, --help   help for TabletExternallyReparented
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout for the total command (default 1h0m0s)
      --server string             server to use for connection (required)
```

### SEE ALSO

* [vtctldclient](../)	 - Executes a cluster management command on the remote vtctld server.

