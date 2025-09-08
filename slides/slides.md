---
# You can also start simply with 'default'
theme: default
# some information about your slides (markdown enabled)
title: Git
fonts:
  sans: Fira Sans
  serif: Fira Sans
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
class: text-center
drawings:
  persist: false
transition: slide-left
mdc: true
---

# Git

## Or: How I Learned to Stop Worrying and Love Version Control

---

```yaml
routeAlias: prereqs
```

# Prerequisites

- Basic <Link to="bash" title="Bash/shell"/> knowledge
- Willingness to learn

---

# Contents

- Elevator Pitch
- Git Features
- GitHub Features
- Contribute to the wiki!

---

```yaml
src: ./pages/Rationale.md
```

---

# Where did Git Come from?

README (Commit: e83c516; Initial revision of "git", the information manager from hell)

```markdown
GIT - the stupid content tracker

"git" can mean anything, depending on your mood.

- random three-letter combination that is pronounceable, and not

  actually used by any common UNIX command. The fact that it is a

  mispronounciation of "get" may or may not be relevant.

- stupid. contemptible and despicable. simple. Take your pick from the

  dictionary of slang.

- "global information tracker": you're in a good mood, and it actually

  works for you. Angels sing, and a light suddenly fills the room.

- "goddamn idiotic truckload of sh\*t": when it breaks
```

---

```yaml
layout: two-cols
```

# Linus Was Sick of It

<v-clicks>

- Development of the **linux kernel** was slowing down due to version mishaps
- Most version control systems were bad, and also proprietary
- Originally, the linux kernel had no version control system, or rather, Linus was the VCS
  - He would merge "patches" that were emailed to him manually
- In 2002, Linus decided to use BitKeeper, a proprietary piece of software, as the VCS for the linux kernel

</v-clicks>

::right::

<img src="/linus.jpeg" width=150em class="m-auto" />

<v-clicks>

- BitKeeper was run by a man named Larry McVoy, who decided to revoke linux developers' access when someone tried to reverse engineer the code base (the developer of rsync)
- Linus then went into seclusion, ceasing all development
  - When he came out, `git` was born

</v-clicks>

---

```yaml
src: ./pages/Git.md
```

---

```yaml
src: ./pages/Github-Features.md
```

---

```yaml
src: ./pages/caveats.md
```

---

```yaml
src: ./pages/wiki.md
```

---

# Helpful Links

- [Software Carpentry tutorial](https://swcarpentry.github.io/git-novice/)
- [Github pull request tutorial](https://docs.github.com/en/get-started/start-your-journey/hello-world)

---

```yaml
src: ./pages/bash.md
```
