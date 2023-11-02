# TinyJS
一个非常mini的编译器，让你对编译原理有个大概的了解。具体demo：将Lisp代码 转成 javascript代码

# 翻译步骤
1. 识别Lisp语言token
2. Lisp token 构建 Lisp AST
3. Lisp AST 转换成 JsAST
4. 遍历JsAST进行代码生成

## 相关资料
- https://citw.dev/tutorial/create-your-own-compiler?p=6

