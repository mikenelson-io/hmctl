## pfctl placement-group destroy

Deletes a specific Placement Group.

```
pfctl placement-group destroy [flags]
```

### Options

```
      --authorization string      Access token for authorization header.
  -h, --help                      help for destroy
  -n, --name string               The name of the Placement Group. (Required)
  -t, --tenant string             The name of the Tenant. (Required)
  -s, --tenant-space string       The name of the Tenant Space. (Required)
      --x-correlation-id string   Add correlation id to header.
      --x-request-id string       Add operation idempotence id to header.
```

### Options inherited from parent commands

```
      --debug-async            Show debug information for asynchronous operations
      --no-wait                Don't wait till asynchronous operation is finished
      --output-format string   Output format (default "pretty")
      --profile string         Configuration profile to use
      --show-http-headers      Show HTTP information about response
```

### SEE ALSO

* [pfctl placement-group](pfctl_placement-group.md)	 - Perform operations on placement-group resources

###### Auto generated by spf13/cobra on 3-Oct-2023
