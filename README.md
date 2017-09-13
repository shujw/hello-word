```
[core]
	repositoryformatversion = 0
	filemode = false
	bare = false
	logallrefupdates = true
	symlinks = false
	ignorecase = true
[remote "hello-word"]
	url = git@github.com:shujw/hello-word.git
	fetch = +refs/heads/*:refs/remotes/hello-word/*
[user]
	name=shujw
	email=shu_jw@126.com
[gui]
	wmstate = normal
	geometry = 841x483+200+200 189 218
[branch "master"]
	remote = hello-word
	merge = refs/heads/master
	atomPrUrl = https://github.com/shujw/hello-word/pull/2
  ```
