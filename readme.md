# libsvm

You might wish to use this updated wrapper by genotrance: https://github.com/genotrance/libsvm.

This repo is provided for backwards compatibility.

Just add this to your .nimble file:

```nim
requires "libsvm_legacy"
```

And change ``import libsvm`` to ``import libsvm_legacy/libsvm``.
