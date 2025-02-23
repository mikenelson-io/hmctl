## pfctl array list

Gets a list of all Arrays.

```
pfctl array list [flags]
```

### Options

```
      --authorization string       Access token for authorization header.
  -z, --availability-zone string   The name of the Availability Zone. (Required)
  -h, --help                       help for list
  -r, --region string              The name of the Region. (Required)
      --x-correlation-id string    Add correlation id to header.
      --x-request-id string        Add operation idempotence id to header.
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

* [pfctl array](pfctl_array.md)	 - Perform operations on array resources

###### Auto generated by spf13/cobra on 3-Oct-2023
