## ターゲットリソースに求められるもの
| ターゲットリソース | 求められるもの（機能） | 備考 |
| ------------------ | :----------------------------: | -------------------------: |
| todo | 誰のtodoかを認識する |  |
|  | todoを登録できる |  |
|  | todoを検索できる |  |
|  | todoを編集できる |  |
|  | todoを削除できる |  |
|  | 自分のtodoだけを確認できる |  |
|  | todoを登録できる |  |
|  | todoの期限を登録できる |  |
|  | todoの期限を変更できる |  |
|  | todoの期限を削除できる |  |
|  | todoをタグで分類（登録）できる |  |
|  | todoをタグごとに表示できる |  |
|  | todoをタグごとに検索できる |  |
|  | todoのタグを削除できる |  |
|  | ユーザー同士でtodoを共有できる |  |
|  | todoを完了状態にすることができる |  |
|  | todoを未完了状態に戻すことができる |  |
| ユーザー | ユーザーを最新状態にする | admin |
|  | ユーザーを登録できる |  |
|  | ユーザーを削除できる |  |
|  | ユーザーとしてログインできる |  |
|  | ユーザーとしてログアウトできる |  |

## 機能とリソースの整理

| 必要とする機能(how) | 何を（what）利用対象 | 誰が(who)利用主体 |
| ------------------ | :----------------------------: | -------------------------: |
| 誰のtodoか区別する | todo | システム |
| todoを登録できる | todo |  ユーザー |
| todoを検索できる | todo |  ユーザー |
| todoを編集できる | todo |  ユーザー |
| todoを削除できる | todo |  ユーザー |
| 自分のtodoだけを確認できる | todo | ユーザー |
| todoを登録できる | todo | ユーザー |
| todoの期限を登録できる | todo | ユーザー |
| todoの期限を変更できる | todo | ユーザー |
| todoの期限を削除できる | todo | ユーザー |
| todoをタグで分類（登録）できる | todo | ユーザー |
| todoをタグごとに表示できる | todo | ユーザー |
| todoをタグごとに検索できる | todo | ユーザー |
| todoのタグを削除できる | todo | ユーザー |
| ユーザー同士でtodoを共有できる | todo | ユーザー |
| todoを完了状態にすることができる | todo | ユーザー |
| todoを未完了状態に戻すことができる | todo | ユーザー |
| ユーザーを最新状態にする(管理) | ユーザー | システム |
| ユーザーを登録できる | ユーザー | ユーザー |
| ユーザーを削除できる | ユーザー | ユーザー |
| ユーザーとしてログインできる | ユーザー | ユーザー |
| ユーザーとしてログアウトできる | ユーザー | ユーザー |

## 機能のグループ分けし、2階層の機能一覧に整理

| グループ| 必要とする機能(how) | 何を（what）利用対象 | 誰が(who)利用主体 |
|  ------------------ | :----------------------------: | -------------------------: | ------------ |
| システム | 誰のtodoか区別する | todo | システム |
| システム | ユーザーを最新状態にする(管理) | ユーザー | システム |
| 未完了 | todoを登録できる | todo |  ユーザー |
| 未完了 | todoを検索できる | todo |  ユーザー |
| 未完了 | todoを編集できる | todo |  ユーザー |
| 未完了 | todoを削除できる | todo |  ユーザー |
| 未完了 | 自分のtodoだけを確認できる | todo | ユーザー |
| 未完了 | todoの期限を登録できる | todo | ユーザー |
| 未完了 | todoの期限を変更できる | todo | ユーザー |
| 未完了 | todoの期限を削除できる | todo | ユーザー |
| 未完了 | todoをタグで分類（登録）できる | todo | ユーザー |
| 未完了 | todoをタグごとに表示できる | todo | ユーザー |
| 未完了 | todoをタグごとに検索できる | todo | ユーザー |
| 未完了 | todoのタグを削除できる | todo | ユーザー |
| 未完了 | ユーザー同士でtodoを共有できる | todo | ユーザー |
| 未完了 | todoを未完了状態に戻すことができる | todo | ユーザー |
| 完了 | todoを完了状態にすることができる | todo | ユーザー |
| 完了 | 完了状態のtodoだけ一覧で確認できる | todo | ユーザー |
| ユーザー | ユーザーを登録できる | ユーザー | ユーザー |
| ユーザー | ユーザーを削除できる | ユーザー | ユーザー |
| ユーザー認証 | ユーザーとしてログインできる | ユーザー | ユーザー |
| ユーザー認証 | ユーザーとしてログアウトできる | ユーザー | ユーザー |