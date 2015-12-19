#以下のURLでこのgithubのホームページにアクセスできる
yasuakiohama.github.io/redirect

#短縮URL https://goo.gl/
goo.gl/4KakGZ

#リダイレクト先
iOS:      https://itunes.apple.com/
Android:  https://play.google.com/
other:    http://www.desunoya.sakura.ne.jp/product/panda/

#作成方法

    cd yourRepository/
    git checkout --orphan gh-pages
    git rm -rf . #これは別にやらなくてもいいかも
    echo "My GitHub Page" > index.html
    git add index.html
    git commit -a -m "First pages commit"
    git push origin gh-pages

    http://yourself-account.github.io/yourRepositoryアクセスするだけ。

#参考
[Githubを使って3分でHPを公開する](http://qiita.com/budougumi0617/items/221bb946d1c90d6769e9)
[gitの空ブランチを作る](http://qiita.com/akiko-pusu/items/7c0a99b8cb37882d2cfe)