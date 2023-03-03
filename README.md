区块链技术指南
======

0.4.0

区块链技术是现在主流数字货币的主要支持技术，被认为在包括金融、物联网、贸易结算等众多领域拥有广泛的应用前景。但由于区块链技术自身还处于快速发展的初级阶段，并且涉及技术领域过杂，为实践应用带来了不小的挑战。

在编写区块链服务平台的过程中，积累了一些工程实践经验，借此机会分享出来，希望能推动区块链技术的更多应用。

本书适用于对区块链技术感兴趣，且具备一定计算机基础知识的读者。

在线阅读：[GitBook](https://www.gitbook.com/book/yeasy/blockchain_guide) 或 [GitHub](https://github.com/yeasy/blockchain_guide/blob/master/SUMMARY.md)。

## 主要版本历史
* 0.4.0: 2016-06-02
    * 添加应用场景分析;
* 0.3.0: 2016-05-12
    * 添加数字货币问题分析;
* 0.2.0: 2016-04-07
    * 添加 hyperledger 项目简介;
* 0.1.0: 2016-01-17
    * 添加区块链简介;

区块链技术自身仍在快速发展中，生态环境也在蓬勃成长。源码开源托管在 Github 上，欢迎参与维护：[https://github.com/yeasy/blockchain_guide](https://github.com/yeasy/blockchain_guide)。贡献者 [名单](https://github.com/yeasy/blockchain_guide/graphs/contributors)。

## 参加步骤
* 在 GitHub 上 `fork` 到自己的仓库，如 `docker_user/blockchain_guide`，然后 `clone` 到本地，并设置用户信息。
```
$ git clone git@github.com:docker_user/blockchain_guide.git
$ cd blockchain_guide
$ git config user.name "yourname"
$ git config user.email "your email"
```
* 修改代码后提交，并推送到自己的仓库。
```
$ #do some change on the content
$ git commit -am "Fix issue #1: change helo to hello"
$ git push
```
* 在 GitHub 网站上提交 pull request。
* 定期使用项目仓库内容更新自己仓库内容。
```
$ git remote add upstream https://github.com/yeasy/blockchain_guide
$ git fetch upstream
$ git checkout master
$ git rebase upstream/master
$ git push -f origin master
```
