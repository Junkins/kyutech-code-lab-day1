# Kyutech Code Lab GitHub講座

<img src="https://ja.wizcase.com/wp-content/uploads/2022/03/GitHub-Logo.png" width="200">

## 目次
1. 講師紹介
2. GitHubとは
3. バージョン管理システムとは
4. エンジニアのSNS
5. GitHubで読める世界のコード
6. GitHubを使い始める(利用するにあたっての注意事項)
7. 小ネタ
8. 質疑応答

## 1. 講師紹介

|  -  |  -  |
| ---- | ---- |
|  名前  |  伊藤潤樹  |
|  GitHub  |  Junkins  |
|  学部  |  生命情報工学科  |
|  会社  |  [Fusic](https://fusic.co.jp/ "Fusic")  |
|  所属  |  IoTチーム  |
|  職種  |  プリンシパルエンジニア  |
|  好きな技術  |  PHP, AWS, SORACOM  |

## 2. GitHubとは
[GitHub](https://github.com/ "GitHub")

### 一言で表すと
- 「ソフトウェア開発のためのプラットフォーム」
- [Where the world builds software](https://github.com/about "GitHub")：世界のソフトウェアを作る場所

### 主な機能
|  -  |  機能  |
| ---- | ---- |
|  1  |  ソースコードのホスティング、バージョン管理  |
|  2  |  ソフトウェア開発者のSNS  |
|  3  |  CI(継続的インテグレーション)：継続的インテグレーション  |
|  4  |  Webサイトのホスティング  |

### 資本関係
[Microsoftによる75億ドル規模のGitHub買収(2018年)](https://japan.zdnet.com/article/35127696/ "Fusic")

## 3. バージョン管理システムとは

### 一言で表すと
- ファイルの変更履歴を管理するシステム

### 主なバージョン管理システム
|  -  |  バージョン管理システム  | タイプ |
| ---- | ---- | ---- |
|  1  |  Git | 分散型 |
|  2  |  SVN  | 集中型 |

- [History](https://github.com/Junkins/kyutech-code-lab-day1/commits/main/README.md)
- [Diff](https://github.com/Junkins/kyutech-code-lab-day1/commit/c5bae121aef87d5f7c0e8c1ad4c0fd911fdfd225)
- [現在のシェア](https://trends.google.com/trends/explore?q=%2Fm%2F05vqwg,%2Fm%2F09d6g,%2Fm%2F012ct9,%2Fm%2F08441_&hl=en-US&tz=&tz= "バージョン管理システムシェア")

### Gitのメリット
 - ブランチが作成しやすい：複雑な差分管理を容易に
 - ローカルリポジトリとリモートリポジトリの分散構成：分業しやすい

### GitHubとは(ここでもう一度)
 - Gitサーバーのホスティングサービス

### Gitを使いこなしたいはここを参照
 - [サル先生のGit入門](https://backlog.com/ja/git-tutorial/)：ヌーラボ社が提供するGit学習サイト
※ 新人時代にお世話になりました。

## 4. エンジニアのSNS

GitHubはソフトウェアエンジニアのSNSとしての一面もあります。

- [83+ million Developers](https://github.com/about "GitHub")：8千3百万人のエンジニア

### GitHubのアカウント名は、エンジニアとしての名前

- しっかり考えて決めましょう。
- 伊藤のアカウント名は「Junkins」、「じゅんき」と「Jenkins」をかけています。

※「Jenkins」は当時のCIツールのデファクトスタンダード

### SNSとして利用してみよう

 - [Junkins](https://github.com/junkins)
 - [matz](https://github.com/matz)
 - [matsumotory](https://github.com/matsumotory)
 - [freeCodeCamp](https://www.freecodecamp.org/japanese/news/learn-programming-by-yourself-freecodecamp-japanese-released/)

## 5. GitHubで読める世界のコード

- GitHubには世界中のソフトウェアのソースコードが公開されている。
- 有名なOSS(Open Source Software)のソースコードに簡単にアクセス

|  OSS名  |  リポジトリ  |
| ---- | ---- |
|  Laravel (illuminate/database) | https://github.com/illuminate/database |
|  CakePHP  | https://github.com/cakephp/cakephp |
|  Django  | https://github.com/djan |
|  python  | https://github.com/python/cpython |
| freeCodeCamp | https://github.com/freeCodeCamp/freeCodeCamp |

※ 公式ドキュメントが最も良いドキュメントだと思いますが、ソースコードを直接読むのも勉強になります。

## 6. GitHubを使い始める(利用するにあたっての注意事項)

### どのプランを利用するか？
- 個人利用の場合は「Free」プランで問題ないと思います。 
- [GitHub 価格](https://github.co.jp/pricing.html)
- [GitHub プライベートリポジトリが無料になりました](https://github.blog/2019-01-07-new-year-new-github/)：良い時代になりました。

### 二要素認証

- [二要素認証を設定する](https://docs.github.com/ja/authentication/securing-your-account-with-two-factor-authentication-2fa/configuring-two-factor-authentication)

### パブリックリポジトリとプライベートリポジトリ
1. アクセスキーなどの情報はGitHubにアップしないほうがよい(プライベートリポジトリであっても)
2. 記憶に新しい流出事件

[gitignore](http://git-scm.com/docs/gitignore)

[三井住友銀行などのソースコードが流出](https://www.itmedia.co.jp/news/articles/2101/29/news107.html)

### OSSライセンス
- 商用利用可能や著作権等が定められている
- [Future Tech Blog](https://future-architect.github.io/articles/20200821/)

## 7. 小ネタ
- [e-ZUKA Tech NightにGitHubのエンジニアが来ていました](https://ko31.github.io/atnd-archive/event/36926.html)
- Octocat ちゃん

![octcat](https://user-images.githubusercontent.com/2044958/174468327-b1ec61a3-fc3d-42fb-833f-8ac0ecea5fb3.png)

