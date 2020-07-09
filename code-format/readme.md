受益于 [`eslint-config-alloy`](https://www.npmjs.com/package/eslint-config-alloy)，其完善的教程为前端代码格式化指明了前进的道路



**当前教程针对 vscode 进行配置**

```json
{
    "eslint.autoFixOnSave": true,
    "eslint.validate": [
        "javascript",
        "javascriptreact",
        {
            "language": "vue",
            "autoFix": true
        },
        {
            "language": "typescript",
            "autoFix": true
        },
        {
            "language": "typescriptreact",
            "autoFix": true
        }
    ],
    "eslint.validate": [
        "javascript",
        "javascriptreact",
        "vue",
        "typescript",
        "typescriptreact"
    ]
}
```



安装 vscode 插件：

- eslint
- prettier