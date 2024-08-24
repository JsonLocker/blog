

create a new repository on the command line

```bash
echo "# blog" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:JsonLocker/blog.git
git push -u origin main
```
OR  push an existing repository from the command line

```bash
git remote add origin git@github.com:JsonLocker/blog.git
git branch -M main
git push -u origin main
```
