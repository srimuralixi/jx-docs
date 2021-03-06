---
date: 2020-03-07T00:59:43Z
title: "jx start protection"
slug: jx_start_protection
url: /commands/jx_start_protection/
description: list of jx commands
---
## jx start protection

Starts protection

### Synopsis

Starts protection checking on an app

```
jx start protection [flags]
```

### Examples

```
  # Start protection
  jx start protection <context> <org/repo>
  
  # For example, to enable compliance on a repopository called "example" in the "acme" organization
  jx start protection compliance-check acme/example
```

### Options

```
  -h, --help   help for protection
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input (default true)
      --verbose      Enables verbose output
```

### SEE ALSO

* [jx start](/commands/jx_start/)	 - Starts a process such as a pipeline

###### Auto generated by spf13/cobra on 7-Mar-2020
