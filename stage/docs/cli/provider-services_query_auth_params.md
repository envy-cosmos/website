## provider-services query auth params

Query the current auth parameters

### Synopsis

Query the current auth parameters:

$ <appd> query auth params

```
provider-services query auth params [flags]
```

### Options

```
      --height int      Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help            help for params
  -o, --output string   Output format (text|json) (default "text")
```

### Options inherited from parent commands

```
      --chain-id string   The network chain ID
      --node string       The node address (default "http://localhost:26657")
```

### SEE ALSO

* [provider-services query auth](provider-services_query_auth.md)	 - Querying commands for the auth module

###### Auto generated by spf13/cobra on 5-Dec-2022