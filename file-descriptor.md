# File Descriptor

A file descriptor is an unique-per-process integer used to identify an opened file.

## Change the soft limit of the maximum number of open file descriptors using Bash Builtin `ulimit`

```bash
ulimit -S -n 1024
```

## Links

- [Bash Builtin `ulimit`](https://github.com/nghianguyentek/bash.shell/blob/main/builtins/ulimit.md#base-builtin-ulimit)