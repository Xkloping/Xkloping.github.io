...或在命令行上创建新的存储库
echo "# demo1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Xkloping/demo1.git
git push -u origin main
