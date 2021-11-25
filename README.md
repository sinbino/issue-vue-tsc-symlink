```shell
$ cd main-proj

$ yarn tsc -p tsconfig.json # success

$ yarn vue-tsc --noEmit # fail
error TS6059: File 'blah/sub-proj/src/types/hello.ts' is not under 'rootDir' 'blah/main-proj'. 'rootDir' is expected to contain all source files.
```
