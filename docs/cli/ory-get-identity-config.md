---
id: ory-get-identity-config
title: ory get identity-config
description: ory get identity-config Get Ory Identities configuration.
---

<!--
This file is auto-generated.

To improve this file please make your change against the appropriate "./cmd/*.go" file.
-->
## ory get identity-config

Get Ory Identities configuration.

### Synopsis

Get the Ory Identities configuration for the specified Ory Network project.

```
ory get identity-config [project-id] [flags]
```

### Examples

```
$ ory get identity-config ecaaa3cb-0730-4ee8-a6df-9553cdfeef89 --format yaml > identity-config.yaml

$ ory get identity-config ecaaa3cb-0730-4ee8-a6df-9553cdfeef89 --format json

{
  "selfservice": {
	"methods": {
	  "password": { "enabled": false }
	}
	// ...
  }
}
```

### Options

```
      --format string   Set the output format. One of default, json, yaml, json-pretty and jsonpath. (default "default")
  -h, --help            help for identity-config
```

### Options inherited from parent commands

```
  -c, --config string   Path to the Ory Network configuration file.
  -q, --quiet           Be quiet with output printing.
  -y, --yes             Confirm all dialogs with yes.
```

### SEE ALSO

* [ory get](ory-get)	 - Get a resource

