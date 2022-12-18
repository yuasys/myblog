# myblog

このリポジトリはGithub-Pagesをより理解するために、いろいろ実験をやりながらその記録をしている場所です。

## これまでの経緯について

このリポジトリのはじめから現在までの経緯についていは[ここ](https://hackmd.io/@yuasys/SJuIkVHbs)に記してあります。

## 実験三昧で楽しい休日を過ごす

### githubに上げたindex.htmlを移動してみる

実験前の状況：新規のパブリックリポジトリにindex.htmlをあ上げて、githubのSettings➜Pages➜Build and development➜Sourceの設定は[GitHub Actions]にしただけ、他のオプションは何もいじっていなかった。
![実験前](images/2022_12_18_8_52.png)  

ちなみにデフォルトで、Actionsに設定されていたワークフローファイル.github/workflows/pages.ymlは[ここ](https://github.com/yuasys/myblog/actions/runs/3722373156/workflow)を参照。

実験の内容：index.htmlを2022-09-17/index.htmlに場所を移動し、ルートのindex.htmlにはリンクだけ置いてみた。

```html
<!DOCTYPE html>
<html lang="jp">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MyBlog|Yuasys-Nob</title>
</head>
<body>
  <p><a href="2022-09-17">2022-09-17</a></p>
  
</body>
</html>
```

実験結果：【成功】最初リンクだけのページが表示され、リンクを押下すると2022-09-17に移動して正しく表示できた。
