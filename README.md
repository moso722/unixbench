# UnixBench
CentOS-based Docker image for the original BYTE benchmark suite.

## Usage

To run all tests:
```
$ docker run moso722/unixbench
```

To choose to run only specific tests (e.g., syscall, see below):
```
$ docker run moso722/unixbench syscall
```

## See also
https://github.com/kdlucas/byte-unixbench
