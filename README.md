# 自用 Rime 配置





## 原仓库位置

[iDvel/rime-ice: Rime 配置：雾凇拼音 | 长期维护的简体词库](https://github.com/iDvel/rime-ice)

详细介绍：[雾凇拼音，我的 Rime 配置及新手指引 - Dvel's Blog](https://dvel.me/posts/my-rime/)

## 修改了什么

- 使用了网络上寻找到的微软输入法皮肤
- 使用shift来将拼音上屏
- 使用`[` `]` 来进行以词定字
- 默认不显示emoji
- 默认只用中文输入法
- `en` `in` `un` 的前后子音的模糊音
- 清空了 `custom_phrase.txt` 用于自定义词语

## 与上游分支合并方法

参考自[合并两个不同远程仓库的Git命令](https://blog.csdn.net/fygkchina/article/details/125735243)

1. 添加新的远程仓库 `git remote add upstream https://github.com/iDvel/rime-ice.git`
2. 拉取上游代码 `git fetch upstream`
3. 创建新分支 `git checkout -b upstream upstream/main`
4. 切回主分支 `git checkout main`
5. 合并分支 `git merge upstream`
6. 打开VSCode等代码工具进行可视化分支合并，之后提交即可
