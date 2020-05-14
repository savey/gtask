# gtask
> Simplify task branch creation！

## Basic usage

```shell
gtask [-]
OPTIONS:
-c [hf]
	h "创建一个 hotfix 分支 base master"
	f "创建一个 feature 分支 base develop"
-d    "删除本地非[master\develop\dev]分支  注意：当使用此选项时、其他选项不生效"
-a|--add    "[file]. 添加到暂存区,并且检测php语法错误！默认为全部改动，但可以添加一个指定文件、注意： 当使用此选项时、其他选项不生效"
```

