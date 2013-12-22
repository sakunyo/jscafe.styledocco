# jsCafe.styledocco

jscafe#17 2013/12/22

[@sakunyo](https://twitter.com/sakunyo)

## サンプルコード
### CSSを使った簡単な例
[https://www.dropbox.com/home/public/jscafe-styledocco/01-css/docs/foo.html](https://www.dropbox.com/home/public/jscafe-styledocco/01-css/docs/foo.html)

    01-css
    ├── docs
    │   ├── foo.html
    │   └── index.html
    └── stylesheets
        └── css
            └── foo.css


### jQuery を使った簡単な例
[https://www.dropbox.com/home/public/jscafe-styledocco/01-css-jquery/docs/foo.html](https://www.dropbox.com/home/public/jscafe-styledocco/01-css-jquery/docs/foo.html)

    01-css-jquery
    ├── docs
    │   ├── foo.html
    │   └── index.html
    └── stylesheets
        └── css
            └── foo.css


### 状態(:hover, :focus の例
[https://www.dropbox.com/home/public/jscafe-styledocco/01-css-state/docs/foo.html](https://www.dropbox.com/home/public/jscafe-styledocco/01-css-state/docs/foo.html)

    01-css-state
    ├── docs
    │   ├── foo.html
    │   └── index.html
    └── stylesheets
        └── css
            └── foo.css


### SASS のドキュメント化
[https://www.dropbox.com/home/public/jscafe-styledocco/02-sass/docs/foo.html](https://www.dropbox.com/home/public/jscafe-styledocco/02-sass/docs/foo.html)

    02-sass
    ├── docs
    │   ├── foo.html
    │   ├── hoge.html
    │   └── index.html
    └── stylesheets
        ├── css
        └── sass
            ├── _hoge.scss
            └── foo.scss


### LESS のドキュメント化
[https://www.dropbox.com/home/public/jscafe-styledocco/03-less/docs/foo.html](https://www.dropbox.com/home/public/jscafe-styledocco/03-less/docs/foo.html)

    03-less
    ├── docs
    │   ├── foo.html
    │   └── index.html
    └── stylesheets
        ├── css
        └── less
            └── foo.less


### SASS と Compass の組み合わせ
[https://www.dropbox.com/home/public/jscafe-styledocco/04-sass-compass/docs/screen.html](https://www.dropbox.com/home/public/jscafe-styledocco/04-sass-compass/docs/screen.html)

    04-sass-compass
    ├── config.rb
    ├── docs
    │   ├── ie.html
    │   ├── index.html
    │   ├── print.html
    │   └── screen.html
    ├── sass
    │   ├── ie.scss
    │   ├── print.scss
    │   └── screen.scss
    └── stylesheets


### bootstrap v3 で試してみた
[https://www.dropbox.com/home/public/jscafe-styledocco/05-bootstrap/docs/bootstrap.html](https://www.dropbox.com/home/public/jscafe-styledocco/05-bootstrap/docs/bootstrap.html)

標準的なディレクトリの場合 less ディレクトリにすべてまとまっているが
実際には bootstrap.less と theme.less のみ別途読み込むはずなのでディレクトリを分けた。
一見すると上手く生成できているようだが、Safari だと grid コンポーネントがバグ？っている。

    05-bootstrap
    ├── README.md
    ├── docs
    │   ├── bootstrap.html
    │   └── index.html
    ├── less
    │   └── bootstrap.less
    ├── modules
    └── theme.less
