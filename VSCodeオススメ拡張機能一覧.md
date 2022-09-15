# VSCodeオススメ拡張機能一覧

基本的に各言語によって追加で拡張機能をインストールしていくが、これがあればいろんな言語で役に立つことが多いものを紹介していく。
それぞれの分野毎に分けていくが、一番下に全てのまとめを置いておく。

## 必須級

とりあえずこれ入れとけばいい、ってやつら。

- zenkaku
  - 全角と半角のスペースを強調する拡張機能
  - 「IME変換の切り替え忘れで全角入力→そのままコーディングしてエラー」を解消できる
  - [zenkaku](https://marketplace.visualstudio.com/items?itemName=mosapride.zenkaku)

- Live Server
  - htmlやcss、jsを仮想ブラウザで実行して動作を確認出来る
  - Web系のプロジェクトをやる時はすごく便利
  - [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

- indent-rainbow
  - インデントを色分けして表示する拡張機能
  - コードブロックが見やすくなる、あと見てて楽しい（）
  - [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)

## Git関係

まず、VSCodeのGitの拡張機能は、PCにGit本体がインストールされていることを前提にしている。
インストールされていないと、Gitの拡張機能が動かないので注意。

- GitHub Pull Requests and Issues
  - GitHubに接続するならほぼ必須な拡張機能
  - pullリクやissueを操作できる
  - [GitHub Pull Requests and Issues](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)

- Git Graph
  - SourceTreeのようなGitのコミットグラフを表示する拡張機能
  - ぶっちゃけこれがあればSourceTreeなんて要らn(ry
  - [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)

- GitLens
  - 誰がどこをコミットしたか見ることのできる拡張機能
  - 誰が何かいたか確認できるようになるのでクソコード書いたらばれるよ
  - ただソースにいろんな情報が増えるので邪魔になる可能性もある
  - [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

## WSL関係

- Remote - WSL
  - wsl内でVSCodeを使用できるようにする拡張機能
  - Windows側でインストールしている拡張機能とWSL側でインストールしている拡張機能は別なので注意
  - [Remote - WSL](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl)

## ターミナル関係

- PowerShell
  - 実はよくわかってないが入れている
  - 恐らくだけどPowerShellのScriptが使えるようになる
  - [PowerShell](https://marketplace.visualstudio.com/items?itemName=ms-vscode.PowerShell)

## その他

個人的に気に入っているもの。雑多なことになると思う。

- Markdown All in One
  - マークダウンに関するあれこれを一括で入れる優れもの
  - これを書いてる時にもすごく働いてくれてる
  - [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

- markdownlint
  - マークダウンの書き方の規則をチェックする拡張機能
  - ドキュメント系は綺麗に書きたいので導入してる
  - [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)

- GitHub Copilot **2022/6/21現在プレビュー版が終了し、有料版になった**
  - 便利の象徴みたいなやべーやつ
  - 利用するのに申請とか必要だけどその分利便性は段違い
  - これ書いてる時もすごく働いてくれてる
  - 怠惰になるので注意
  - **現在は有料になったが、GitHubEducationに登録すれば無料で使えたりする**
  - [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)

- GitHub Markdown Preview
  - GitHubで表示されるマークダウンのプレビューを表示する拡張機能
  - ドキュメント整備にとても役立つパッケージで色々入ってる
  - [GitHub Markdown Preview](https://marketplace.visualstudio.com/items?itemName=bierner.github-markdown-preview)

- Remote - Containers
  - Dockerのコンテナをフル活用するための拡張機能
  - DockerDesktopがインストールされていること前提なので注意
  - [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

- Marp for VS Code
  - markdownでスライド（パワポのようなもの）を書くことが出来るようになる拡張機能
  - PDFへの出力ができ、プレビューもVSCode内で出来る。
  - 世界のドキュメントが全部markdownになればいいと思ってる（過激派）
  - [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)

## 拡張機能一覧

|            拡張機能             |                             説明                             |
| :-----------------------------: | :----------------------------------------------------------: |
|             zenkaku             |            全角と半角のスペースを強調する拡張機能            |
|           Live Server           |    htmlやcss、jsを仮想ブラウザで実行して動作を確認出来る     |
|         indent-rainbow          |            インデントを色分けして表示する拡張機能            |
| GitHub Pull Requests and Issues |            GitHubに接続するならほぼ必須な拡張機能            |
|            Git Graph            |   SourceTreeのようなGitのコミットグラフを表示する拡張機能    |
|             GitLens             |       誰がどこをコミットしたか見ることのできる拡張機能       |
|          Remote - WSL           |         wsl内でVSCodeを使用できるようにする拡張機能          |
|           PowerShell            |       恐らくだけどPowerShellのScriptが使えるようになる       |
|          markdownlint           |       マークダウンの書き方の規則をチェックする拡張機能       |
|       Markdown All in One       |      マークダウンに関するあれこれを一括で入れる優れもの      |
|         GitHub Copilot          |       便利の象徴みたいなやべーやつ、怠惰になるので注意       |
|     GitHub Markdown Preview     | GitHubで表示されるマークダウンのプレビューを表示する拡張機能 |
|       Remote - Containers       |         Dockerのコンテナをフル活用するための拡張機能         |
|        Marp for VS Code         |              markdownでスライドをかける拡張機能              |

## 更新履歴

- 2022-\*-\*
  - 新規作成
- 2022-07-20
  - Marp for VS Code 追加
  - Remote - Containers 追加
