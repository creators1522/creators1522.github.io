# creators1522.github.io
creators公式サイト

git push -fはしないでね
作業するときは別branchを作ってそこでやるとよし
git push orgin [branch名]でpushし、pull requestiを作ってね
といってもお今のところ書くこと特になし
酔ってるので追記必須


# ファイル構成

## -docs

//これ以下の者がビルドの対象

  ### -_data
  
  サイトで使うデータ。json形式とyml形式とかサポートしてるのは公式を見ろ。
  
  ### -_includes 
  
  使いまわすコードとかはここに突っ込んでインクルードしよう
  
  ### -_layouts
  
  ページレイアウトのテンプレを入れる。マークダウンで書いたやつがこれにしたがって変換されて公開される。
  
  ### -_posts
  
  投稿記事を入れる
  
  ### -sass
  
  sass形式のを入れる。cssの似てるやつらしい？（知らん）。
  
  ### -assets
  
  js、cssとか入れる。imageとかもここか？？
  
  ### -.gitignore
  
  むししろ
  
  ### -_config.yml
  
  設定項目
  
  ### -Gemfile
  
  rubyのパッケージ管理。
  もうちょっと具体的なページの構想が出てこればもっとファイル分けしてもいいかもね
