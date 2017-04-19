# Session title

Intellij plugins with Kotlin!

# Description

*** Think catchy first sentense!!! ***

I have been maintaining more than 10 Intellij Plugins using Kotlin. https://plugins.jetbrains.com/author/shiraji

This talk will introduce these plugins and show pros/cons about using Kotlin. 

The expected plugins I will talk about are followings:

* [find-pull-request](https://github.com/shiraji/find-pull-request)

My first plugin written in Kotlin. It add right click menu and jump to pull request page.

* [gradle-intellij-plugin wizard](https://github.com/shiraji/intellij-plugin-with-gradle-wizard)

Custom wizard for [gradle intellij plugin](https://github.com/JetBrains/gradle-intellij-plugin). This plugin is combination of Kotlin and Java

* [Android Color Manager]( https://github.com/shiraji/color-manager )

Intellij plugin with Tool window

* [Databinding Support]( https://github.com/shiraji/databinding-support )

Lots of custom intentions

## Pros

* 文法が楽
* JavaのAPIをそのまま使える。

## Cons

* GUI designerがないので、ToolwindowやWizardなどSwingに依存している部分は若干Javaを書く必要が出て来る。
* 過去のIDEバージョン対応する場合、Kotlin Runtime Libが必要になってくる。
* Kotlinのbeta/alphaユーザが時々Kotlin側の問題で落ちた場合、そのクラッシュレポートをしてくる。
