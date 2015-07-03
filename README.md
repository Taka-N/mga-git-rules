# MGAのGit/GitHub運用ルール

あまりガチガチのルールにしてもつまらないので、必要最低限にとどめましょう:octocat:

- [GitHub Flow](https://gist.github.com/Gab-km/3705015)で運用する
- メンバーのレビューや相談が必要なときはPull requestを活用する
- その日の終わりには作業内容を必ずpushして帰る
- ブランチ名は小文字ハイフン区切りで統一 `sample-branch-name-1234`
- トピックブランチに適宜masterの変更内容をマージし、いつでも簡単にマージできるようにしておく
- 強制pushはしない（どうしても必要な場合は全関係者と調整の上で行うこと）
- Fast-forward可能でもマージコミットを作る（--no-ffを指定）
