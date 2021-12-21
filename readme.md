用于日常学习资料总结
稀疏检出

 git config core.sparseCheckout true
.git/info/sparse-checkout


删除和远程仓库的连接
git remote remove origin

查看和远程仓库的连接
git remote -v

添加远程仓库连接
git remote add origin git@xxxxxx.git


加tag 
git tag -a <版本号> <SHA值> -m "<备注信息>"

推送所有标签git push origin --tags
本地删除标签
Git tag -d v1.2
删除远程标签
git push origin --delete <tagname>


