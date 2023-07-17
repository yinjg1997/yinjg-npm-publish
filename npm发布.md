# npm 发布

## package 中的发布信息

```json
{
  "name": "shang-utils", // 包名，必须要独一无二
  "version": "1.0.0", // 版本号
  "author": "xxx", // 作者
  "description": "common toolkit", // 描述信息
  "keywords": ["utils", "format", "money", "phone"], // 关键词，提升SEO
  "repository": {
    // 代码托管位置
    "type": "git",
    "url": "https://github.com/xxx/shang-utils"
  },
  "license": "ISC", // 许可证
  "homepage": "https://your-package.org", // 包的主页或者文档首页
  "bugs": "https://github.com/xxx/shang-utils/issues", // 用户问题反馈地址
  "main": "index.js", // 入口文件
  "scripts": {
    // 存放可执行脚本
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "dependencies": {
    // 运行依赖
  },
  "devDependencies": {
    // 开发依赖
  }
}
```
