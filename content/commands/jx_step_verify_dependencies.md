---
date: 2019-07-18T18:18:58Z
title: "jx step verify dependencies"
slug: jx_step_verify_dependencies
url: /commands/jx_step_verify_dependencies/
---
## jx step verify dependencies



### Synopsis



```
jx step verify dependencies [flags]
```

### Options

```
      --dir string   The directory of the repository to validate, there should be a dependency-matrix dir in it
  -h, --help         help for dependencies
```

### Options inherited from parent commands

```
  -b, --batch-mode                Runs in batch mode without prompting for user input (default true)
      --config-file string        Configuration file used for installation
      --install-dependencies      Enables automatic dependencies installation when required
      --no-brew                   Disables brew package manager on MacOS when installing binary dependencies
      --skip-auth-secrets-merge   Skips merging the secrets from local files with the secrets from Kubernetes cluster
      --verbose                   Enables verbose output
```

### SEE ALSO

* [jx step verify](/commands/jx_step_verify/)	 - verify [command]

###### Auto generated by spf13/cobra on 18-Jul-2019