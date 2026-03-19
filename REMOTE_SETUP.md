# Remote Repository Setup

## Current Remotes
[Вставьте вывод git remote -v]
backup  git@github.com:mrRCooperJey/techstart-api-backup.git (fetch)
backup  git@github.com:mrRCooperJey/techstart-api-backup.git (push)
origin  git@github.com:mrRCooperJey/techstart-api.git (fetch)
origin  git@github.com:mrRCooperJey/techstart-api.git (push)
origin  git@github.com:mrRCooperJey/techstart-api-backup.git (push)

## Tracking Branches
[Вставьте вывод git branch -vv]
  develop cd773aa [origin/develop] version 1.1.0-dev
* main    f76f7c2 Merge branch 'main' of github.com:mrRCooperJey/techstart-api

## Fork Workflow Summary
- Original repository: [https://github.com/vityak007/awesome-calculator]
- Fork repository: [https://github.com/mrRCooperJey/awesome-calculator]
- Upstream configuration: [git remote set-url upstream git@github.com:vityak007/awesome-calculator.git] - если я верно понял и помню - она

## Backup Strategy
- Primary remote: origin
- Backup remote: backup
- Sync command: [git remote set-url --add --push origin git@github.com:mrRCooperJey/techstart-api-backup.git]
backup  git@github.com:mrRCooperJey/techstart-api-backup.git (fetch)
backup  git@github.com:mrRCooperJey/techstart-api-backup.git (push)
origin  git@github.com:mrRCooperJey/techstart-api.git (fetch)
origin  git@github.com:mrRCooperJey/techstart-api.git (push)
origin  git@github.com:mrRCooperJey/techstart-api-backup.git (push)

не совсем понимаю, что за команда требуется, на этом шаге была лютая путаница опять же, без ИИ не вывез

## Lessons Learned
Без ИИ невероятно трудно разобраться, некоторые моменты вообще опущены в теории, своим умом догадаться не представляется возможным