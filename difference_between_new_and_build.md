# railsのnewとbuildの違いについて

- 基本的にはない
- 昔は`build`じゃないと子モデルの関連を表現できなかった
- 今は`build`でも`new`でもできる
- 慣習的にuser.comments.buildのように、子モデル生成の際にはbuildが利用されるらしい
