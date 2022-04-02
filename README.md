# Introduction
This is the code template repository for the tutorial of cloud-writing on software [YUQUE](https://www.yuque.com/) and synthesize the markdown files to generate hexo blog on the Github-Page.

这是《语雀+hexo+github持续化部署+shoka主题》中使用的博客源码示例仓库。

[中文说明在此](https://dream.emerge.cyou/yuque/%E3%80%90%E6%95%99%E7%A8%8B%E3%80%91%E8%AF%AD%E9%9B%80+hexo+github%E6%8C%81%E7%BB%AD%E5%8C%96%E9%83%A8%E7%BD%B2+shoka%E4%B8%BB%E9%A2%98/)

# Usage
1. Please clone this example repository to your conputer.
2. Prepare tokens and SSH keys on Github and YUQUE. Set up two repositories on Github.
3. Set up web-knowledge repository(ZHI SHI KU) on YUQUE and set it with a web hook address.
4. Set up cloud function on cloud service (for example, Tencent).
5. Delete *.git* hidden folder of the example repository.
6. Edit the following files as you need:
  - `origin-example\.github\workflows\main.yml.example` please rename it to `main.yml` and edit.
  - `.\_config.yml`
  - `.\_config.shoka.yml`
  - `.\package.json`
  - `.\source\about\index.md`
  - `.\source\friends\index.md` & `.\source\friends\_data.yml`
  - `.\themes\shoka\source\images` change the images to your own.
  - `.\themes\shoka\languages` change your prefered language and traslation of some words.
7. Clone one of your repository as the origin code for hexo blog to your computer and copy all files from example repository to it.
8. Use Git or other upload tools to upload the repository to Github.
9. Wait for Github Actions running and check out if there is any problem.
10. You may raise up problems in ISSUES of this repository.

中文说明请参考上面给出的网址，如果有问题可以在Issue或原文评论区提出，谢谢。

# Reference
- Hexo：https://hexo.io/
- Theme Shoka：https://github.com/amehime/hexo-theme-shoka
This repository has used parts of the code showed as listed. 
本代码模板包含以上仓库和软件的部分内容。
The tutorial is based on following articles or documations: 
感谢以下文档为我完成这篇教程提供的帮助。

1. [Hexo：语雀云端写作，Github Actions持续集成](https://blog.csdn.net/z_johnny/article/details/104629805/)
2. [语雀云端写作Hexo+Github Actions+COS持续集成](https://www.yuque.com/1874w/1874.cool/roeayv)
3. [Hexo 主题 Shoka 使用文档](https://shoka.lostyu.me/computer-science/note/theme-shoka-doc/)
4. [使用git分支保存hexo博客源码到github](https://zhuanlan.zhihu.com/p/71544809)
5. [github文件夹有白色箭头并且不能打开的解决办法](https://blog.csdn.net/xiebaochun/article/details/114143346)
6. [生成新的 SSH 密钥并将其添加到 ssh-agent](https://docs.github.com/cn/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
7. [yuque-hexo使用文档](https://github.com/x-cold/yuque-hexo)
8. [解决包含 GitHub Actions Workflow 的分支无法推送的问题](https://blog.walterlv.com/post/github-push-failed-without-workflow-scope.html)
Thank you for your sharing precious experiences.
