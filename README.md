# UBadge
A script help to generate CI/CD badge

## 这个脚本可以在workflow与运行后更新你的勋章
例子:
![ubadge](/ubadge.png)

vs

![github](/origin.png)


## 使用
复制`workflow.yaml`到你的.github/workflows/目录下，你可以随意重命名这个文件。

复制`ubadge.py`到你的仓库根目录下，请不要修改这个文件的文件名称。

在`workflow.yaml`中根据注释修改你的参数。

注意，默认情况下，这个脚本会把勋章状态放到markdown文档中的`<!---ubadge-auto-list-begin-->`和`<!---ubadge-auto-list-end-->`之间。

Enjoy!

示例项目: https://github.com/moe-org/utopia
