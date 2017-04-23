
# NJU2
校内社区问答网站

## Developer Guide
0. Clone from https://github.com/liyuanWu/nju2.git
1. Create new branch for the new feature u want to add (eg. searchUser)
2. Finish the feature and push to remote repo
3. Create pull request to merge into master
4. After other developers have reviewed the change, merge into master

## 本地部署
> 0. git clone https://github.com/yxfanxiao/zhihu.git
> 1. 启动mongodb (如果你端口不是27017，在configure.js改)
> 2. cd && npm start (不需要npm install)
> 3. visit: 127.0.0.1:3000

随意用一个符合邮箱或手机格式的账号注册，首页一开始没有内容是因为还没有关注问题。
* 发布问题（至少包含1个话题）
* 关注问题
* 回答问题
* 点赞或down （点赞后刷新页面看到自己是否点过赞）
* 'x条评论'是因为二级评论还没做
* 再发布一个含有刚发布问题话题的问题
* 查看相关问题
* 回到主页，可以看到关注问题的新的回答（这里只能看赞数，暂时没有细做点赞和关注，点击回答可以进入问题进行操作）
* 搜索只有根据问题题目的简单模糊搜索
* 我的主页可以修改头像，看到自己的Profile
* 设置可以修改基本资料

## 主线功能
部分开发记录见log.md
* 注册 + 登录 + 设置 √
* 提问 + 回答 + 点赞 √
* 关注问题 + 动态推送 √
* 关注人 + （赞、提出问题、关注问题、回答问题）  正在做ing

