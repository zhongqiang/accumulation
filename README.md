#first modify!

git config --global user.email "zqdeng_cn@yahoo.cn"
git config --global user.name "zhongqiang"



touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/zhongqiang/accumulation.git
git push -u origin master

#Push an existing repository from the command line

git remote add origin https://github.com/zhongqiang/accumulation.git
git push -u origin master


git clean -n


git clone https://github.com/zhongqiang/accumulation.git
