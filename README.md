# Minecraft-WorkSpace 導入手順

このページでは、Minecraft-WorkSpaceサーバーに参加するための準備方法を説明します。

PCやMinecraft MODの知識がなくても、上から順番に進めれば導入できます。

---

# 必要なもの

以下の2つが必要です。

- Minecraft Java Edition
- Prism Launcher

MODは自分で1個ずつインストールする必要はありません。

必要なMODはMinecraft起動時に自動でダウンロード・更新されます。

---

# 1. Prism Launcherをインストールする

Prism Launcherをインストールしてください。

公式サイト：

https://prismlauncher.org/

Windowsの場合は、基本的にWindows向けの通常版を使用してください。

インストール後、Prism Launcherを起動します。

---

# 2. Minecraftアカウントを追加する

Prism Launcherを起動したら、

`右上のアカウント`
↓
`アカウントを管理`
↓
`Microsoftアカウントを追加`

を選択します。

ブラウザが開くので、Minecraft Java Editionを所有しているMicrosoftアカウントでログインしてください。

---

# 3. Minecraft-WorkSpaceを追加する

配布された

`Minecraft-WorkSpace.zip`

をダウンロードしてください。

ZIPファイルは解凍しなくて大丈夫です。

Prism Launcherを開いて、

`起動構成を追加`

を押します。

左側から

`インポート`

を選択してください。

その後、

`参照`

から先ほどダウンロードした

`Minecraft-WorkSpace.zip`

を選択します。

最後に

`OK`

を押してください。

しばらく待つと、Prism Launcherに

`Minecraft-WorkSpace`

が追加されます。

---

# 4. Minecraftを起動する

追加された

`Minecraft-WorkSpace`

をダブルクリックしてください。

または、

`Minecraft-WorkSpace`
↓
`起動`

を押してください。

---

# 初回起動について

初回起動時は、必要なMODを自動でダウンロードします。

そのため、普段より起動に時間がかかる場合があります。

画面上でダウンロード処理が表示されても正常です。

処理が終わると、そのままMinecraftが起動します。

---

# 2回目以降

基本的にやることはありません。

Prism Launcherを開いて、

`Minecraft-WorkSpace`
↓
`起動`

だけで大丈夫です。

サーバー側でMODが追加・更新された場合も、Minecraft起動時に自動で更新されます。

---

# MODを自分で追加する必要はありますか？

ありません。

Minecraft-WorkSpaceでMellrisによって必要なMODは自動管理されています。

基本的には、

`mods`

フォルダを自分で編集しないでください。

手動でMODを追加・削除すると、正常に起動できなくなる場合があります。

---

# 「MODを更新してください」と言われた場合

基本的には何もしなくて大丈夫です。

一度Minecraftを終了してから、

Prism Launcher
↓
Minecraft-WorkSpace
↓
起動

を行ってください。

最新版が自動的に取得されます。

---

# Minecraftが起動しない場合

まず以下を試してください。

1. Minecraftを終了する
2. Prism Launcherを終了する
3. Prism Launcherをもう一度起動する
4. Minecraft-WorkSpaceを起動する

それでも起動しない場合は、エラー画面のスクリーンショットを送ってください。

自分でMODを削除したり、設定を変更したりする必要はありません。

---

# Javaについて

Prism LauncherにはJavaを自動で管理する機能があります。

Javaに関するエラーが出た場合は、自己判断でJavaを入れ直さず、管理者に連絡してください。

---

# よくある質問

## Q. Fabricって何ですか？

MinecraftでMODを動かすために使用しているシステムです。

特に操作する必要はありません。

---

## Q. Packwizって何ですか？

Minecraft-WorkSpaceで使用するMODを自動で管理・更新する仕組みです。

参加者が操作する必要はありません。

---

## Q. MODを自分でダウンロードする必要はありますか？

ありません。

必要なMODは起動時に自動で取得されます。

---

## Q. MODが更新されたらどうすればいいですか？

いつも通りMinecraftを起動してください。

自動で更新されます。

---

## Q. Prism Launcher以外でも参加できますか？

Minecraft-WorkSpaceではPrism Launcherを前提に環境を管理しています。

特別な理由がない限り、Prism Launcherを使用してください。

---

# 使用している自動更新システム

Minecraft-WorkSpaceでは、

Prism Launcher
+
Packwiz
+
GitHub

を利用してMOD構成を管理しています。

MOD構成の変更は管理者側で行われます。

参加者側では、Minecraftを起動するだけで最新の環境が自動的に反映されます。

---

# 注意事項

以下の操作は、特に理由がない限り行わないでください。

- modsフォルダのMODを削除する
- modsフォルダに勝手にMODを追加する
- Fabric Loaderを変更する
- Minecraftのバージョンを変更する
- 起動前コマンドを削除する
- packwiz-installer-bootstrap.jarを削除する

正常に動かなくなった場合は、自分で修復しようとせず管理者に連絡してください。
