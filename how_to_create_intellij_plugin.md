# Session title

Intellij plugins with Kotlin!

# Description

今まで15以上のIntellij pluginをリリースしました。

https://plugins.jetbrains.com/author/shiraji

このうち、10プロジェクトでKotlinを採用しました。それらのプラグインを紹介しつつ、Kotlinを採用して良かった点・悪かった点を上げていきたいと思います。

紹介する予定のプラグインは以下です。

* find-pull-request(https://github.com/shiraji/find-pull-request)

初めてフルKotlinで作成したプラグインです。対象の行のコミットが入ったPull Requestを見つけて、そのPull RequestのURLを開くというものです。

* gradle-intellij-plugin wizard

gradle intellij pluginを便利にするwizardを作りました。これはKotlinとJavaの混合プロジェクトです。

* Android Color Manager ( https://github.com/shiraji/color-manager )

Tool windowを使ったIntellijプラグインです。

* Databinding Support ( https://github.com/shiraji/databinding-support )

custom intentionを多く実装しているAndroid用のプラグインです。

## 良かった点

* 文法が楽
* JavaのAPIをそのまま使える。

## 悪かった点

* GUI designerがないので、ToolwindowやWizardなどSwingに依存している部分は若干Javaを書く必要が出て来る。
* 過去のIDEバージョン対応する場合、Kotlin Runtime Libが必要になってくる。
* Kotlinのbeta/alphaユーザが時々Kotlin側の問題で落ちた場合、そのクラッシュレポートをしてくる。
