# git-SVN

### git-SVN安装

在win平台git-SVN默认是安装的，而linux平台需要手动安装

```bash
sudo apt install  git-svn
```

### 拉取已经存在的SVN仓库

```bash
git svn clone -r5791:HEAD [svn_url] [new_name] 
```

r5791为最新的版本号，查看版本号可直接通过浏览器访问svn地址r5791为最新的版本号，查看版本号可直接通过浏览器访问svn地址

new\_name可以给导入的项目取个新的名称，也可以不写，默认和svn名称一致

### 本地提交到SVN

```
 git svn dcommit
```

### 同步远端到本地

```bash
git svn fetch
```

