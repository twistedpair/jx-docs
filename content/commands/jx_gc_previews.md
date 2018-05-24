---
date: 2018-05-24T21:04:49Z
title: "jx gc previews"
slug: jx_gc_previews
url: /commands/jx_gc_previews/
---
## jx gc previews

garbage collection for preview environments

### Synopsis

Gargabe collect Jenkins X preview environments.  If a pull request is merged or closed the associated preview environment will be deleted.

```
jx gc previews [flags]
```

### Examples

```
  jx garbage collect previews
  jx gc previews
```

### Options

```
  -b, --batch-mode   In batch mode the command never prompts for user input
      --headless     Enable headless operation if using browser automation
  -h, --help         help for previews
      --no-brew      Disables the use of brew on MacOS to install or upgrade command line dependencies
      --verbose      Enable verbose logging
```

### SEE ALSO

* [jx gc](/commands/jx_gc/)	 - Garbage collects Jenkins X resources

###### Auto generated by spf13/cobra on 24-May-2018