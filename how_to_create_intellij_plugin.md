# Session title

Intellij plugins with Kotlin!

# Description

*** Think catchy first sentense!!! ***

I have been maintaining more than 10 Intellij Plugins using Kotlin. https://plugins.jetbrains.com/author/shiraji

This talk will introduce these plugins and show pros/cons about using Kotlin. 

The expected plugins I will talk about are followings:

* find-pull-request(https://github.com/shiraji/find-pull-request)

My first plugin written in Kotlin. 
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
