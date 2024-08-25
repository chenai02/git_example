`git rebase -i`的一些误区：

假设日志有`A-B-C-D`，其中`HEAD`为A，现在我想将A和D合并，那么需要将D移动到A的下面，顺序变为将`D-A-B-C`，然后将D前面的`pick`改为`squash`或者`fixup`。因为`squash`或者`fixup`是将信息合并到上一条日志中。