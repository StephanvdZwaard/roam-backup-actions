# roam-backup-actions

2022-07-05: Switched from roam-to-git to [Roam2Github](https://www.notion.so/Instructions-to-switch-from-roam-to-git-to-Roam2Github-aec58ad1b56e4547ba97e006c8cc120a) by creating a separate repo for the workflow and backups.

2022-07-27: Set EDN back-up option to false [[see common issues](https://www.notion.so/Issues-c8232da0ee85446bb433f2b490373ba2)]. Back-up wasn't working yet because of out-of-memory error since my Roam graph was too large for EDN back-up. Therefore, change the yml-file accordingly and only back-up markdown and json files. 
