---
date: 2019-06-08T15:56:35Z
title: "jx step create devpod"
slug: jx_step_create_devpod
url: /commands/jx_step_create_devpod/
---
## jx step create devpod

Creates the DevPod workspace files

### Synopsis

Creates the DevPod workspace files

```
jx step create devpod workspace [flags]
```

### Examples

```
  # create the DevPod Workspace files
  jx step create devpod workspace
```

### Options

```
  -d, --dir string               The workspace directory to write to (default "/workspace")
  -h, --help                     help for devpod
      --vscode                   If enabled also setup the VS Code settings to enable the devpodsh Terminal script
      --vscode-home string       The VS Code default home dir file relative to the workspace home dir (default "/root")
      --vscode-settings string   The VS Code settings file relative to the workspace home dir (default ".local/share/code-server/User/settings.json")
```

### Options inherited from parent commands

```
      --advanced-mode             Advanced install options. This will prompt for advanced install options
  -b, --batch-mode                Runs in batch mode without prompting for user input (default true)
      --install-dependencies      Enables automatic dependencies installation when required
      --log-level string          Sets the logging level (panic, fatal, error, warning, info, debug) (default "info")
      --no-brew                   Disables brew package manager on MacOS when installing binary dependencies
      --skip-auth-secrets-merge   Skips merging the secrets from local files with the secrets from Kubernetes cluster
      --verbose                   Enables verbose output
```

### SEE ALSO

* [jx step create](/commands/jx_step_create/)	 - create [command]

###### Auto generated by spf13/cobra on 8-Jun-2019