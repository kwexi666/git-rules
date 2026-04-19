## A2. rebase, cherry-pick и amend, чтобы пересоздать историю
#### Нельзя переписать историю — можно создать новую
- `git commit --amend --no-edit` — заменить последний коммит ветки
- `git rebase <upstream>` — перенести коммиты на другую базу
- `git rebase -i <upstream>` — интерактивный rebase
- `git rebase --continue` — продолжить после конфликта
- `git rebase --abort` — отменить rebase
- `git cherry-pick <commit>` — применить коммит