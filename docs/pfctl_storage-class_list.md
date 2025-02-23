## pfctl storage-class list

Gets a list of all Storage Classes.

```
pfctl storage-class list [flags]
```

### Options

```
      --authorization string      Access token for authorization header.
  -h, --help                      help for list
      --storage-service string    The name of the Storage Service (Required)
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

* [pfctl storage-class](pfctl_storage-class.md)	 - Perform operations on storage-class resources

###### Auto generated by spf13/cobra on 3-Oct-2023
