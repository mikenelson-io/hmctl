## pfctl volume eradicate

Eradicates a specific Volume.

```
pfctl volume eradicate [flags]
```

### Options

```
      --authorization string      Access token for authorization header.
  -h, --help                      help for eradicate
  -n, --name string               The name of the Volume. (Required)
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

* [pfctl volume](pfctl_volume.md)	 - Perform operations on volume resources

###### Auto generated by spf13/cobra on 3-Oct-2023
