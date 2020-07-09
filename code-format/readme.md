受益于 [`eslint-config-alloy`](https://www.npmjs.com/package/eslint-config-alloy)，其完善的教程为前端代码格式化指明了前进的道路



**当前教程针对 vscode 进行配置**

```json
{
    "[vue]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[json]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "[typescript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    },
    "eslint.validate": [
        "javascript",
        "javascriptreact",
        "vue",
        "typescript",
        "typescriptreact"
    ],
}
```



安装 vscode 插件：

- eslint
- prettier



`eslint-config-alloy` 支持 javascript, typescript, vue, react 各语言的代码检查，使用的是各语言最受欢迎的代码检查库，再根据 alloy-team 自己的业务特点进行自定义的检查规则。



对自定义没有特别要求，也可以直接使用各语言的代码检查库的官方推荐配置：

- javascript: `eslint`
- typescript: `@typescript-eslint/eslint-plugin`
- vue: `eslint-plugin-vue`
- react: `eslint-plugin-react`

