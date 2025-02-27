---
sidebar_position: 3
---

# アイテム取り寄せ機能

アイテム取り寄せ機能とは作業台などに設計図を入れることで一定の範囲内のストレージから必要物資を集めてくれます
これによりTEKストレージなどに資材を入れておくことで大量のアイテムを運ばないでものを制作できるようになります
また[ARKショップ](/docs/Feeling)で建材の設計図を購入することで大量の建材の制作が楽になります
これを使うには[サブスクリプション](docs\arkapi\arkshop.md)が必要になります

[サブスクリプション](/docs/Feeling)   | 通常 | ドードー | ラプトル | レックス | ギガノト
  ------------------ | --------| -------- | ------- | ------- |---------
  使用の可否　　　　　　| ×   | ×  | ○     | ○     | ○
  恐竜からの取り寄せ　　　　　　| ×   | ×  | ×     | ×     | ○

## 使い方
<img src="\img\arkapi\pull2.jpg" />

①作業台を開き制作タブに移ります<br></br>
②右上のエングラム表示を無効にします<br></br>
③取り寄せたい素材の設計図をpullフォルダにドラッグアンドドロップしてフォルダに入れます<br></br>
④pullフォルダを開き、設計図があることを確認し、チャット欄(全体チャット)に```/p 個数```（全て半角）と打ちます一つな場合は数は未記入でもよいです<br></br>
例:```/p```→1個分取り寄せる　```/p 10```→10個分取り寄せる

※一部代替アイテムなどは取り寄せ出来ません

## 取り寄せ範囲
<img src="\img\arkapi\pull1.jpg" />

いちばん左の金庫から⑩までの距離は生物からの取り寄せができます<br></br>
いちばん左の金庫から⑲までの距離はストレージなどからの取り寄せができます

## 注意点
- puiiフォルダがない場合は作業台を置きなおすか、自分でpullフォルダを制作することで機能します
- EXOメックやアルゲンタビスなどに取り寄せることはできません
- 周りのストレージだけでなく作業台やレプリケーターからも取り寄せます
- エレメントは燃料のため取り寄せないようになっています