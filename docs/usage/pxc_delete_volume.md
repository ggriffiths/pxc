## pxc delete volume

Delete a volume in Portworx

### Synopsis

Delete a volume in Portworx

```
pxc delete volume [NAME] [flags]
```

### Examples

```

  # Delete the volume by name muvolume
  pxc delete volume myvolume
```

### Options

```
  -h, --help   help for volume
```

### Options inherited from parent commands

```
      --config string    Config file (default is $HOME/.pxc/config.yml)
      --context string   Force context name for the command
      --v int32          [0-4] Log level verbosity
```

### SEE ALSO

* [pxc delete](pxc_delete.md)	 - Delete an object in Portworx

###### Auto generated by spf13/cobra on 6-Nov-2019