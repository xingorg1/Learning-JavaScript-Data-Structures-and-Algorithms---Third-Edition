# Learning-JavaScript-Data-Structures-and-Algorithms---Third-Edition
学习JavaScript数据结构与算法（第三版）

## 资料
1、本书代码仓库：https://github.com/PacktPublishing/Learning-JavaScript-Data-Structures-and-Algorithms-Third-Edition. 
2、本书作者github：https://github.com/loiane. 
3、本书勘误：https://www.ituring.com.cn/book/2653. 

📒笔记：https://github.com/xingorg1/Learning-JavaScript-Data-Structures-and-Algorithms---Third-Edition/wiki

## 结构
- nodeServer
``` bash
.
├─ README.md
├─ package.json
└─ src # 开发环境
   ├─ index.html # 入口文件
   └─ main.ts
```

## 环境配置 http-server
- [http-server使用教程](https://www.npmjs.com/package/http-server)，先安装npm包、并根据教程配置npm 脚本。
- 参数配置如下
  - -c-1：禁用缓存
  - --cors：设置请求头“Access-Control-Allow-Origin ”，允许CORS跨域资源共享
