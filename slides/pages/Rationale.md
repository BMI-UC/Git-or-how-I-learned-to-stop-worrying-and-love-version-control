---
layout: center
---

# Why Do We Need Version Control?

<v-clicks>

````md magic-move
```shell
mydissertation.txt
```

```shell
mydissertation.txt
mydissertation-v2.txt
```

```shell
mydissertation.txt
mydissertation-v2.txt
mydissertation-v3.txt
```

```shell
mydissertation.txt
mydissertation-v2.txt
mydissertation-v3-broken.txt
mydissertation-v2a.txt
```

```shell
mydissertation.txt
mydissertation-v2.txt
mydissertation-v3-broken.txt
mydissertation-v2a.txt
```

```shell
mydissertation.txt
mydissertation-v2.txt
mydissertation-v3-broken.txt
mydissertation-v2a.txt
mydissertation-vfinal.txt
```

```shell
mydissertation.txt
mydissertation-v2.txt
mydissertation-v3-broken.txt
mydissertation-v2a.txt
mydissertation-vfinal.txt
mydissertation-vfinal-no-really-this-is-the-final-version-I-swear.txt
```

```shell
mydissertation.txt # now with git!
```
````

- As the number of files increases, so do version headaches
- You **will** make mistakes

</v-clicks>

<!--
We've all been here, projects grow in complexity very fast. Even a simple project like this one, which only contains one file, may become complicated enough to require several versions. When collaboration gets thrown into the mix, it becomes even messier.
-->

---

```yaml
layout: two-cols-header
```

# What Does Git Do?

::left::

<v-clicks>

- all the versions for every file in your project can be saved
  at once

```shell
git add . # tells git what to save (everything)
git commit -m "My first commit!" # tell git to save
```

- Enables asynchronous collaboration

</v-clicks>

::right::
<SlidevVideo autoplay loop>

<source src="/word-versions.mp4">
</SlidevVideo>

<!--
You can think of Git as a very fancy version of the version control systems you may have already used, such as the one in word displayed here.

Git differentiates itself from the version control systems in word documents by applying to the entire project, as well as with some features we will talk about later that enable asynchronous collaboration.
-->
