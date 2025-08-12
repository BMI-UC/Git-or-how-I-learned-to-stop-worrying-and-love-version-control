---
---

# Caveat

- Git is not well suited to large binary files
- This includes images, videos, compiled programs, etc
- This problem can be alleviated with [`git annex`](https://git-annex.branchable.com/git-annex/) (local) and [`git lfs`](https://git-lfs.com/) (remote)

### Why?

- git aims to take the least amount of storage space
- Binary diffs are large and can't be chained together effectively
- compressing and uncompressing the binary files can be difficult

### Rule of thumb

- Any file below 50mb is fine, though try to keep the total size below 1GB
- Try to change the binary files as little as possible
