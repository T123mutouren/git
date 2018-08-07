## git error  and doc

#### git 冲突合并

	git stash save //将修改暂存 恢复到上一次更新的状态
	git pull 	   // 拉去代码
	git stash pop  // 弹出保存的修改进行合并

#### composer 更新时忽略版本号

	composer install --ignore-platform-reqs
	or
	composer update --ignore-platform-reqs