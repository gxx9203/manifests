# example usage:

run below command on cmd windows
```
repo init --repo-url=https://github.com/gxx9203/repo.git --no-repo-verify --repo-branch=master -u https://github.com/gxx9203/manifests.git -m default.xml

repo init -u  git@github.com:gxx9203/manifests.git -m default.xml
```
hexo
```
repo init --repo-url=https://mirrors.tuna.tsinghua.edu.cn/git/git-repo --no-repo-verify --repo-branch=stable -u git@github.com:gxx9203/manifests.git -m hexo.xml
```

# TODO
github repo .how to use ssh to push ?

temp solve method  only input one time username and password
```
git config --global credential.helper store
```

