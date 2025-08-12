---
layout: two-cols
routeAlias: bash
---

# Bash

- Bash, zsh, fish, etc are all _Shells_, programs that
  provide a textual way to interact with the computer
- Bash is the most popular linux shell, but most shells
  understand a shared syntax
- Shells are _interpreters_ for their respective languages, similar to python
  and R
- The primary unit of execution is called a _shell command_, which can be written
  in any language

::right::

- The syntax for a shell command is simple:

```bash
COMMAND ARGS
```

- Shell commands are actually file names: `which COMMAND` will output the
  location

```bash
git commit -m "hello world"
```

- The `git` command is run with args: `commit`, `-m`, `"hello world"`

<goBack from="prereqs"/>

```bash
vim main.py
```

- The `vim` command is run with args: `main.py`
- This command starts the `vim` editor and loads `main.py` into it
