# 06
## New branch作成と切り替え
```bash
git branch develop

git switch develop
Switched to branch 'develop'

git branch
* develop
  main
```

## 変更内容
This is a change on develop branch
```bash
(base) iMac-82:06 zhouwentong$ git add .
(base) iMac-82:06 zhouwentong$ git commit -m "Update on develop branch"
[develop 919aeaa] Update on develop branch
 1 file changed, 14 insertions(+)
