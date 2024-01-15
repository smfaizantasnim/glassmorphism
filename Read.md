echo "# glassmorphism" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/smfaizantasnim/glassmorphism.git
git push -u origin main

git checkout -b main
git add .
git commit -m "Initial commit"


git push -u origin main

git checkout main

git pull origin main
