# goBLC
综述：学习孔壹学院练习，用golang实现bitcoin系统。
学习资源：
http://edu.kongyixueyuan.com/course/3

1.使用go mod来管理依赖关系
（1）使用go mod init + 项目名称初始化
（2）使用go mod tidy 下载所需要的包

2.在windows系统下
使用go build -o main.exe main.go编译

3.运行main.exe 文件可以查看命令行指令如下：
Usage:
        addresslists -- 输出所有钱包地址.
        createwallet -- 创建钱包.
        createblockchain -address -- 交易数据.
        send -from FROM -to TO -amount AMOUNT -- 交易明细.
        printchain -- 输出区块信息.
        getbalance -address -- 输出区块信息.
        test -- 测试.

4.该项目使用boldDB非关系型数据库。数据库使用参考：
https://github.com/boltdb/bolt.git

5.该项目使用golang语言实现bitcoin运行原理，如：POW工作量证明机制、UTFO，公私钥机制、数字签名、转账。通过该课程对bitcoin系统会有更加全面的认识，对学习区块链思维有较大帮助。
