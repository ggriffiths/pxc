## pxc plugin list

List all visible plugin executables

### Synopsis


		List all available plugin files on a user's PATH.

		Available plugin files are those that are:
		- executable
		- anywhere on the user's PATH
		- begin with "pxc-"

```
pxc plugin list [flags]
```

### Options

```
  -h, --help        help for list
      --name-only   If true, display only the binary name of each plugin, rather than its full path
```

### Options inherited from parent commands

```
      --pxc.config string       Config file (default is $HOME/.pxc/config.yml)
      --pxc.config-dir string   Config directory (default "/home/lpabon/.pxc")
      --pxc.context string      Force context name for the command
      --pxc.token string        Portworx authentication token
      --pxc.v int32             [0-3] Log level verbosity
```

### SEE ALSO

* [pxc plugin](pxc_plugin.md)	 - Provides utilities for interacting with plugins

###### Auto generated by spf13/cobra on 5-Mar-2020