# laarc/arc0

A mirror of [arc0.tar](https://github.com/laarc/arc0/releases/download/1/arc0.tar), the first release of Arc.

See also:

* [laarc/arc3.1](https://github.com/laarc/arc3.1)
* arc0 vs arc3.1 ([html](https://rawgit.com/laarc/notebook/master/arc0-3.1.html) | [txt](https://rawgit.com/laarc/notebook/master/arc0-3.1.txt))

```
$ wget https://github.com/laarc/arc0/releases/download/1/arc0.tar
$ cat arc0.tar | shasum -a 256
9b7a00b2f486c6fcaab0e01a3c5e165fcfaf96fbef5f38a9bc7dd944ac78c7c0  -
$ tar xvf arc0.tar
$ cd arc0
$ ls -1 | grep '\.scm$' | xargs cat | wc -l
    1157
$ ls -1 | grep '\.arc$' | xargs cat | wc -l
    3450
```

