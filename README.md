参考资料：

1. [Jib构建你的第一个java镜像](https://blog.csdn.net/mo_xingwang/article/details/81096188)

2. [springboot+Jib+Maven+Idea+Docker 实践](https://blog.csdn.net/shenhonglei1234/article/details/87967088)

大致步骤：

1. 注册dockerhub账号
2. 按jib的官方说明下载docker-credential-wincred，放到系统path下
3. 运行demo

优点：

jib无需dockerfile，可直接在远程私有仓库创建应用镜像

缺点：

需要在服务器手动pull镜像，创建容器，比较麻烦
