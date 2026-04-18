## S3. Манипуляции через ссылки, нет ссылки — в мусор
#### HEAD — текущая ссылка, tag — фиксированная ссылка, branch — движущаяся за HEAD ссылка
#### checkout — перемещение на ветку или коммит, reset — перемещение с веткой на коммит
#### Видно то, на что есть ссылки, остальное — мусор
- `git tag`
- `git tag <tagname>`
- `git branch`
- `git branch -av`
- `git branch <branchname>`
- `git branch -d <branchname>`
- `git checkout <commit>`
- `git checkout <branch>`
- `git checkout -b <new_branch>`
- `git reset --hard <commit>`
- `git reflog show <ref>`
- `git reflog`
- `git gc`