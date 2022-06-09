# 操作说明-使用Token

## 使用Token

发请求的时候，在URL中添加参“spaceServiceToken=您生成的token”，即可通过Token调用服务内容。

示例：在服务URL的"?"号后面，增加 \&spaceServiceToken=\*\*\*。

不加token时会报401错误：

![不加token时会报401错误](<../../.gitbook/assets/3 (1)>)

添加token参数后，可正常访问服务：

![添加token参数访问服务](<../../.gitbook/assets/4 (1)>)
