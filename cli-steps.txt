For MarkDown, You can preview the file with markdown in VS Code studio as well to preview .

mkdir git-markdown
cd git-markdown
git init -b main\n
vi Readme.md
git add . && git commit -m "initial commit"\n
git status
git remote add origin https://github.com/RahulPanchal0110/git-markdown.git
git remote -v
git push -f origin main
