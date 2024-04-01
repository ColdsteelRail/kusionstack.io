## kusion init

Initialize the scaffolding for a demo project

### Synopsis

This command initializes the scaffolding for a demo project with the name of the current directory to help users quickly get started.

 Note that target directory needs to be an empty directory.

```
kusion init [flags]
```

### Examples

```
  # Initialize a demo project with the name of the current directory
  mkdir quickstart && cd quickstart
  kusion init
  
  # Initialize the demo project in a different target directory
  kusion init --target projects/my-demo-project
```

### Options

```
  -h, --help            help for init
  -t, --target string   specify the target directory
```

### Options inherited from parent commands

```
      --profile string          Name of profile to capture. One of (none|cpu|heap|goroutine|threadcreate|block|mutex) (default "none")
      --profile-output string   Name of the file to write the profile to (default "profile.pprof")
```

### SEE ALSO

* [kusion](index.md)	 - Kusion is the Platform Orchestrator of KusionStack

###### Auto generated by spf13/cobra on 29-Mar-2024