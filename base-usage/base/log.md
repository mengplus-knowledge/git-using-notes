# log

### 显示日志

```sh
git log --graph  --oneline --all
```

\--graph 图形化显示

\--oneline 每个提交显示一行

\--all 所有分支，包括远程分支

### 显示本地所有操作记录

```bash
git reflog 
```

跟 **log**类似，但是reflog更像是本地所有操作的历史记录，如果有错误的提交修改都能从这里找回，而log是提交到远程的记录
