---
title: "Set user information in Git"
tags:
  - "Programs/Git/Commands/config"
  - "Programs/Git/Topics/Configuration"
date_created: 2021121012T0514
---
You can set various information such as your [[Email address|email address]], username, and other information in [[Git]] using `git config` in a single repository like so:

```bash
git config user.foobar "foobarbaz"
# Sets the variable `user.foobar` to `foobarbaz`.
# Where user.foobar should be interpreted as `section.key`.
# Where ``"foobarbaz"`` should be interpreted as the plain text value of `user.foobar`.
```
With the `--global` flag, you can set it globally:
```bash
git config --global user.foobar "foobarbaz"
# Sets the variable `user.foobar` to `foobarbaz`.
# Where user.foobar should be interpreted as the secondary key.
# Where ``"foobarbaz"`` should be interpreted as the plain text value of `user.foobar`.
# Where `--global` sets the key globally.
```

The following is a list of values supported by Git:
- `user.email`
- `user.name`