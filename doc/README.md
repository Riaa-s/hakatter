# gitの使い方

## branch
### 今どこに自分がいるか確認
```bash
git branch
```
### upstreamのリポジトリにあるmasterを起点として新しいブランチを作りつつ[name]に移動
```bash
git checkout upstream/master -b [name]
```
### 登録しているリモートリポジトリ（ここでいうupstream）を確認
```bash
git remote -v
```
### リモートリポジトリにあるmasterブランチをローカルのブランチに反映させる
```bash
git pull upstream master
```
### ローカルでの変更をコミットの対象として扱う
```bash
git add -A
```
### updateというメッセージ付きでコミット（ローカルでの一時保存）
```bash
git commit -m "update"
```
### ローカルでコミットしたものをリモートリポジトリにあるmasterに反映させる
```bash
git push upstream master
```
