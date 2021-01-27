echo "# github-upload" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mw853820/github-upload.git
git push -u origin main
