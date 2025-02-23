## pfctl volume update

Updates a specific Volume.

```
pfctl volume update [flags]
```

### Options

```
      --authorization string                 Access token for authorization header.
      --destroyed                            True if the resource should be destroyed. Set --destroyed=true to destroy. Set --destroyed=false to recover.
      --display-name string                  The display name of the resource.
  -h, --help                                 help for update
      --host-access-policies string          List of Host Access Policies.
  -n, --name string                          The name of the Volume. (Required)
      --placement-group string               The name of the Placement Group.
      --protection-policy string             The name of the Protection Policy.
      --size int                             Size of the object in bytes. Accepts K, M, G, T or P units for specifying units in kibibytes, mebibytes etc. 5M is equal to 5242880 bytes.
      --source-link string                   Source volume snapshot reference.
      --source-volume-snapshot-link string   Source volume snapshot reference.
      --storage-class string                 The name of the Storage Class.
  -t, --tenant string                        The name of the Tenant. (Required)
  -s, --tenant-space string                  The name of the Tenant Space. (Required)
      --x-correlation-id string              Add correlation id to header.
      --x-request-id string                  Add operation idempotence id to header.
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
