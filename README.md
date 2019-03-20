# markdown-typesetting

組版できるマークダウンエディタを作る

## 目的

一般の人でも Word や Excel に振り回されることなく、 Markdown 記法を覚えただけで印刷用ドキュメントを作成できるようなアプリケーションを作成する。  
似たような機能を開発している人は存在するが、多くは GitHub を介さなければならず、開発者向けであるため、普通の人たちでも簡単に使えるようにしたい。


### 想定ユーザー

- 卒論を書きたい大学生
- 会社で説明書を作らないといけない会社員

  
## 初期バージョン概要

### 画面

- 左側にマークダウンエディタ表示
- 右側にエディタに記述したものを組版形式でリアルタイム確認（レイアウト画面）
  - レイアウトは、[Markdown＋CSS組版での技術系同人誌制作時の環境](https://yoshikawaweb.com/markdown-css.html)を参考
  - 印刷に関しては、[新詳説DTP基礎 改訂四版 \(MdN DESIGN BASICS\)](https://amzn.to/2FqKMQz)を参考

### マークダウンエディタ詳細

- 基本的なマークダウンのみをサポート
  - [markedjs/marked](https://github.com/markedjs/marked) で作成
  
### レイアウト画面詳細

- 標準的なテキストサイズで見出しを表示
  - あとで調べる
- 見出しごとにフッターを表示する  
- 大見出しごとにページ送りする
- ページ番号を表示する
- デザインはとりあえずよくある感じの本を見本に一種類
- (ページ送りできる) <- SPA を想定しそうで別の方法でもいいかも
  

## そのうちやりたい（上の方が優先度高い）

- 数式の入力
- SPA でレイアウト画面のページ送り
- 段組、行間、禁則処理などの基本的な組版のレイアウト
- CSS の編集




