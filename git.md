

git config--global user.name //创建账号
git config--global user.email

git init  创建仓库
git add .              //把全部文件从工作区移到暂存区
git commit -m"提交的提示信息" // 把文件从暂存区移动到本地git仓库
git commit -a -m""           //快速提交 必须以前提交过一次 //可以跳过暂存区
git checkout  -- 文件名         //仓库代码覆盖工作区

删除
git rm-f文件名      // Git仓库和工作区中同时移除
git rm-cached     //只删除本地仓库

git log       //查看日志
git reflog  //查看完整日志
git reset --hard 版本号 //回退到某个版本
git status 查看状态