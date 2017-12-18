# llvm_CFGPass
llvm control flow graph分析
---

This is a dynamic LLVM Pass which is to give the basicblocks id and profile the ids.

### Build the pass by doing that:

- create a folder by `mkdir build`

- cd the build folder and build it: `cd build && cmake ../`

- make the project: `make`

### execute by the Pass

`opt -load /the/path/of/libCFGPass.so -CFG /the/path/of/llvm/IR/file`

then there are the outputs.
