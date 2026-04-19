## R3. Явное сопоставление локальных веток с upstream
- git branch -vv — вывести список локальных веток с указанием привязанных к ним upstream-веток
- git branch -u <upstream> [<branchname>] — задать upstream-ветку
- git push -u origin HEAD — создать ветку и связать её
- git checkout <remote_branchname> — создать локальную ветку из удалённой
- git pull = git pull origin
- git pull --ff-only — только fast-forward
- git pull --rebase — сделать rebase вместо merge
- git pull --rebase --autostash — сохранить изменения и сделать rebase
- git config --global push.default simple — режим push