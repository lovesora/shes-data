## Bazel build overview

Bazel breaks a build into discrete steps, which are called actions. Each action has inputs, output names, a command line, and environment variables. Required inputs and expected outputs are declared explicitly for each action.

Incremental builds is one of the major advantages of Bazel. “Incremental” means that Bazel will only rebuild the parts of the source code that is relevant to a change.

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTc2MzQyOTgyNiwtMTcyNTA5MTQ4MV19
-->