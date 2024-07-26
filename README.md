echo "# Population Information System" >> README.md
echo "venv/" >> .gitignore
echo "__pycache__/" >> .gitignore
git init
git add README.md .gitignore
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/population-info-system.git
git push -u origin main
