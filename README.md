# ClassIsland.SimpleGitInfoGenerator

一个简单的 Git 信息源生成器，会将构建时的 Git 信息以字符串常量的形式生成到 `ClassIsland.GitInfo` 静态类中，便于在应用内获取 Git 构建信息。

包含的属性：

| 属性 | 说明 |
| --- | --- |
| `CommitHash` | 提交 ID |
| `Branch` | 当前分支 |
| `Tag` ` | 最近的 Tag 名称 |

## 许可

本项目基于 [MIT License](./LICENSE) 获得许可。
