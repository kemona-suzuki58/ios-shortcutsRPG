# ios-shortcutsRPG
These ios-shortcuts are made in Japanese.And I use google translate for English.  

# このショートカットについて(Japanese)  

このショートカットでは、本格的なRPGをショートカットのみで遊ぶことができます。簡単なコマンド操作で初心者からでも楽しめます。  
難しい呪文要素や、回復要素は今のところ実装されていません。  

## 遊び方

まずはじめに「はじめから」を選択し、主人公の名前を設定してください。ただし、途中にスペースを含めてしまうとセーブデータが破損シてしまうおそれがあるので、スペースの前までのみを認識する仕様になっているのでご了承ください。また、文字数制限はありません。  

### 移動コマンド

このショートカットでは、この世界をXとYの2軸として、マップを表現しています。そのゲーム機で言う十字キーを再現したようなものだと思っていただければいいです。  
要するに、主人公を移動させるコマンドのようなものです。  
*下の方の設定に設定項目あり*  

### ステータスコマンド

このショートカットでは、主人公、敵にそれぞれ「体力」「攻撃」「防御」が設定されていて、自分の数値を確認できます。  
それだけではなく、今の設定項目の詳細だったり、今いる場所等も確認できます。  

### 設定コマンド

#### 移動速さ

ここでは、移動コマンドを使うときの移動の速さを1~5の間で変更することができます。  
具体的には、1のときは、座標1ずつの移動となり、5のときは、座標5ずつの移動となります。  

#### 難易度

Ver.1.0.0 現在、難易度は未実装の機能となっています。  
ここで、今後出てくる敵のレベルを変更したりできるようになる予定です。  

#### セーブデータ保存

只今うまく設定ができておらず、この機能を使用するのはあまりおすすめしません。  
もし、実装できましたら、ここにワンタップでセーブできる機能を作ろうと考えています。  
実装までもうしばらくお待ち下さい。  

### セーブコマンド

このコマンドでは、先程紹介したセーブデータ保存のやり方も含め、  
デフォルトではメモAppを開き、それを手動で保存していただく形となっています。  
用途により、ショートカットの項目をご自身で変更したりすることで別の場所に保存していただいたりすることも可能です。  

## 注意事項等

### ゲームを始める前に(ショートカットに書いてある注意事項をそのまま)

~~このゲームは複数のショートカットにより成り立っています。すべてダウンロードして、設定した上でプレイしてください。~~  
また、新しいフォルダを使って仕分けることで管理がしやすくなります。  
~~変更箇所はコメントで記されています。この作業がなければゲームを楽しむことができませんのでご了承ください。~~  
*このショートカットは作成当初複数のショートカットを使う予定でしたが、結局変数の引き継ぎができなかったりで1つのショートカットによりまり立っています。*  

このショートカットRPGは、セーブデータをメモに保存して管理しています。  
セーブデータの入っているメモの内容を変更すると、データが正常に読み込めません。  
また、ロード機能はショートカットの仕様上ありませんので、文字列をコピーして次回起動時に「つづきから」というところから入力してください。  
また、セーブデータ番号を毎回振っているので1番大きな番号が最新のセーブデータとなっています。なお、セーブデータは、更新によって形式が変わったりする場合があります。  
そのときには移行するためのショートカットの公開も行うつもりですのでご確認ください。  

このショートカットは、まだまだ不完全となっています。もし、ゲームが進行不可となるような状況になりましたらこちらの方にお知らせいただくか、TwitterのDMでも対応いたします。  

このショートカットはiPadのアラートアクションや、メニューアクションを使用しているため、それ以外の画面を触るとアラート、メニューが引っ込んでショートカットの実行が終了してしまいます。  
くれぐれもこまめなセーブをし、誤タップのないようにお願い致します。  

また、ショートカット上では、無限に動作を続けるコマンドが無いため、代わりに、1000000000000回(10兆回)繰り返す仕組みとなっています。  
流石にこんな人はいないと思いますが、10兆回何かしらのコマンドをする前にセーブをしてください。  

最後に、このショートカットは本当に多くのアクションを使用しているので。起動中はiPad,iPhoneの動作が重くなる場合があります。  
もし、プレイが困難な場合は潔く諦めるしかありません。軽量化はほとんど不可能に近いと考えております。  

## これまでの更新情報

### main

#### Ver.1.0.0
RPGのおおよその土台を完成させました。 

#### Ver.1.0.1
レベルアップの際に上がる能力値の値を上方修正しました。
今まで1固定になってしまっていたのを
体力 1~3
攻撃 1~2
防御 1~2
の乱数になるようにしました。

#### Ver.1.1.0
今回のアップデートでは、今までこのゲームでネックだった、ロード機能の不便さだったり、メモの圧迫を軽減することができるようになりました。
これにより、数タップでデータをロードする事が可能となります。
また、新しく誤タップや誤操作でゲームを終了してしまった時のためのバックアップ機能を追加しました。
これを使用するにはセーブデータ機能をONにする必要がありますが、
毎移動ごとにバックアップフォルダーにデータが追加されます。

### Cheat save data creation

#### Ver.1.0.0

簡単な機能のみをつけた初期型です

#### Ver.1.0.1

今まで使っていたセーブデータを変更できるような機能を加えました。

#### Ver.1.1.0

最新のセーブ形式に合わせる形を取りました。

### AutoPlay

#### Ver.1.0.0

ios-shortcutRPGVer1.1.0を改造してフルオートでコマンドもアラートも通知も出ずに放置しているだけでレベルが上がるやりがいのない物
ios-shortcutsRPGと合わせてお楽しみください。

## 今後の更新情報

今後は、移動した座標に合わせてイベントを起こす機能を追加したり、大きなゲームの進行に影響を与えるバグの改善をする予定です。  

## 細かい仕様説明

只今書き込み中です。しばらくお待ち下さい。  


# About this shortcut (English)

With this shortcut, you can play a full-fledged RPG with just the shortcut. Even beginners can enjoy it with simple command operations.  
Difficult spell elements and healing elements have not been implemented so far.  

## how to play

First of all, select "From the beginning" and set the name of the main character. However, if you include a space in the middle, the save data may be damaged, so please note that the specifications are such that only the front of the space is recognized. Also, there is no character limit.  

### Move command

In this shortcut, the map is represented with this world as the two axes of X and Y. You can think of it as a reproduction of the cross key on the game console.  
In short, it's like a command to move the hero.  
*There is a setting item in the lower setting*  

### Status command

In this shortcut, "physical strength", "attack", and "defense" are set for the main character and the enemy respectively, and you can check your own numerical value.
Not only that, you can also check the details of the current setting items and where you are.  

### Configuration command

#### Moving speed

Here you can change the speed of movement when using the move command between 1 and 5.  
Specifically, when it is 1, it moves by 1 coordinate, and when it is 5, it moves by 5 coordinates.  

#### difficulty

As of Ver.1.0.0, the difficulty level is an unimplemented function.  
Here, you will be able to change the level of enemies that will appear in the future.  

#### Save data

I haven't set it up right now, so I don't recommend using this feature.  
If I can implement it, I'm thinking of creating a function that can be saved with one tap here.  
Please wait for a while until implementation.  

### Save command

With this command, including the save data saving method introduced earlier,  
By default, you open the Memo app and save it manually.  
Depending on the purpose, you can change the shortcut item yourself and save it in another location.  

## Precautions, etc.

### Before starting the game (keep the notes on the shortcut)

~~This game is made up of multiple shortcuts. Please download all, set and play.~~  
Also, sorting using new folders makes it easier to manage.  
~~Changes are noted in the comments. Please note that you will not be able to enjoy the game without this work.~~  
*This shortcut was originally planned to use multiple shortcuts, but in the end it was not possible to inherit variables, so it stands out with one shortcut.*  

This shortcut RPG saves and manages save data in a memo.  
If you change the contents of the memo containing the save data, the data cannot be read normally.  
Also, since the load function is not available due to the specifications of the shortcut, copy the character string and enter it from the place where "Continued" at the next startup.  
Also, since the save data number is assigned every time, the largest number is the latest save data. The format of save data may change due to updates.  
At that time, we will also publish a shortcut for migration, so please check.  

This shortcut is still incomplete. If the game becomes unprogressable, please let us know or we will respond by DM on Twitter.  

Since this shortcut uses the alert action and menu action of the iPad, if you touch any other screen, the alert and menu will be retracted and the execution of the shortcut will end.  
Please save diligently and avoid accidental taps.  

Also, on the shortcut, there is no command that continues to operate indefinitely, so instead, it is a mechanism that repeats 1000000000000 times (10 trillion times).
I don't think there is anyone like this, but please save it before issuing any command 10 trillion times.  

Finally, because this shortcut uses so many actions. The operation of iPad and iPhone may become slow during startup.  
If it is difficult to play, you have no choice but to give up. We believe that weight reduction is almost impossible.  

## Update information so far

### main

#### Ver.1.0.0
We have completed the approximate foundation of the RPG.

#### Ver.1.0.1
The value of the ability value that goes up when leveling up has been revised upward.
Until now it was fixed at 1
Physical strength 1-3
Attack 1-2
Defense 1-2
I tried to make it a random number.

#### Ver.1.1.0
With this update, you can now reduce the inconvenience of loading and the pressure on your notes, which has been a bottleneck in this game.
This makes it possible to load data with just a few taps.
In addition, we have added a new backup function in case the game is terminated due to an erroneous tap or operation.
To use this, you need to turn on the save data function,
Data is added to the backup folder for each move.

### Cheat save data creation

#### Ver.1.0.0

It is an early model with only simple functions.

#### Ver.1.0.1

We have added a function that allows you to change the save data that you have been using.

#### Ver.1.1.0

I took the form to match the latest save format.

### AutoPlay

#### Ver.1.0.0

It is a worthwhile thing that the level goes up just by modifying ios-shortcutRPG Ver1.1.0 and leaving it unattended without issuing commands, alerts or notifications with full auto
Please enjoy it together with ios-shortcuts RPG.

## Future updates

In the future, we plan to add a function to raise an event according to the moved coordinates and fix a bug that affects the progress of a big game.   

## Detailed specification explanation

I'm writing now. Please wait for a little while.  
