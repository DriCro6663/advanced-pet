# OBS Scene Collection: Advanced-PET

![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/DriCro6663/advanced-pet)
![GitHub](https://img.shields.io/github/license/DriCro6663/advanced-pet)

[![Demo-Youtube-v1.0.0](https://img.youtube.com/vi/LzrnZg5Scx4/0.jpg)](https://www.youtube.com/watch?v=LzrnZg5Scx4)

## [- README.md for the English version is here -](./README-EN.md)

ロックマンエグゼの PET をイメージした [OBS](https://obsproject.com/ja) のシーンコレクションです。

> [ロックマンエグゼ AXESS ~ Beast+ までの PET: Advanced-PET 系](https://www.nicovideo.jp/watch/sm30540016)

[Scene Collection Manager](https://obsproject.com/forum/resources/scene-collection-manager.1434/) を使用して、シーンコレクションをインポートしてください。

## はじめ

* [N-guchino](https://exe-rockman.net/) 様の [PET 画面](https://exe-rockman.net/wp-content/uploads/2020/06/pet06.png)

    <details>
    <summary>画像：N-guchino 様の PET 画面</summary>

    [![N-guchino_PET](https://exe-rockman.net/wp-content/uploads/2020/06/pet06.png)](https://exe-rockman.net/make_a_pet_extra01/)

    </details>

* [かみや](https://www.nicovideo.jp/user/19608348) 様の [PET 画面](https://www.nicovideo.jp/watch/sm36826926)

    <details>
    <summary>画像：かみや 様の PET 画面</summary>

    [![ロックマンエグゼ風仮想背景](https://img.cdn.nimg.jp/s/nicovideo/thumbnails/36826926/36826926.61672808.original/r1280x720l?key=288286928b9953df497529e34b1532da9f672da9b8e034b847091eaf6e526f75)](https://www.youtube.com/watch?v=lhHvjWNb8AA)

    </details>

* [ロックマンエグゼ AXESS ED アニメーション](https://www.nicovideo.jp/watch/sm30540016)

    <details><summary>画像：ロックマンエグゼ AXESS ED アニメーション</summary>

    [![光とどく場所ノンテロ](https://img.cdn.nimg.jp/s/nicovideo/thumbnails/30540016/30540016.original/r1280x720l?key=52b270c1df982983aa0f64c9f029287bb0965a98f31a33d56cacd9c0dc75bc5a)](https://www.nicovideo.jp/watch/sm30540016)

    </details>

上記のものを参考にさせていただきました。

略儀ながら、ここに感謝の意を表します。

## 概要

[Scene Collection Manager](https://obsproject.com/forum/resources/scene-collection-manager.1434/) を使用して作成した、ロックマンエグゼの PET をイメージしたシーンコレクションのバックアップです。

## 使い方

1. [OBS](https://obsproject.com/ja) と [SAMMI](https://github.com/SAMMISolutions/SAMMI-Official/releases) をインストールしてください。<br>※私は SAMMI を C:\Program Files\SAMMI に置いています。

2. 以下ののプラグインを [OBS](https://obsproject.com/ja) にインストールしてください。

    * [Scene Collection Manager](https://obsproject.com/forum/resources/scene-collection-manager.1434/)
    * [Move transition](https://obsproject.com/forum/resources/move-transition.913/)
    * [StreamFX](https://obsproject.com/forum/resources/streamfx-for-obs%C2%AE-studio.578/)

        > 2023/02/01 現在、私は [StreamFX 0.12.0 Alpha 151](https://github.com/Xaymar/obs-StreamFX/releases/tag/0.12.0a151) を使用しています。ご使用の OBS によって、StreamFX の Version を選んでご使用ください。

3. 下記リンクを参考に [OBS](https://obsproject.com/ja) と [SAMMI](https://github.com/SAMMISolutions/SAMMI-Official/releases) の接続設定を行ってください。<br>※元々、LioranBoard 2 と SAMMI は同じソフトなので参考になるはずです。

    > [LioranBoard 2の導入方法・TwitchとYouTube Liveとの連携](https://kurocha.jp/lioranboard2-setup)
    >
    > [【OBS】最強の無料ストリームデック LioranBoard2 導入ガイド配信【 VTuber / 毘沙門天ゆるいこ】](https://www.youtube.com/live/Vf76nyIeeng?feature=share)

4. [Release](https://github.com/DriCro6663//releases) からシーンコレクションをダウンロードして圧縮ファイルを解凍してください。

5. 下記リンクを参考に [Scene Collection Manager](https://obsproject.com/forum/resources/scene-collection-manager.1434/) を用いてシーンコレクションの json ファイルをインポートしてください。

    > [OBSのバックアップを簡単便利にするプラグイン](https://kurocha.jp/obs-scene-collection-manager)

    <details><summary>
    画像：シーンコレクションバックアップのインポート
    </summary>
    
    ![kurocha-import-01](https://kurocha.jp/wp-content/uploads/2022/05/2022-05-09_17h12_27-1.jpg)
    
    ![kurocha-import-02](https://kurocha.jp/wp-content/uploads/2022/05/2022-05-09_17h14_04.jpg)
    
    ![kurocha-import-03](https://kurocha.jp/wp-content/uploads/2022/05/2022-05-09_17h17_53.jpg)
    
    > [OBSのバックアップを簡単便利にするプラグイン](https://kurocha.jp/obs-scene-collection-manager)
    </details>

    <details><summary>
    ※インポート後に問題があった場合、以下のサウンド設定を参考にしてください。
    </summary>

    * BGM: [深層世界](https://oto.how/sound/457), 再生速度：150 %, 音量：-32.0 db
    * ED: [Seeds for the future / Free BGM Ver.](https://www.d-elf.com/free-bgm/free-bgm-ending), 音量：-16.0 db
    * PET-boot-se: [サウンドデザイン-04](https://koukaon.g-sozai.com/se-532.html), 再生速度：50 %, 音量：-8.0 db
    * task-bar-se: [Cyber11-1](https://otologic.jp/free/se/cyber02.html), 再生速度：200 %, 音量：+8.0 db
    * loading-se: [Cyber13-1](https://otologic.jp/free/se/cyber02.html)
    * scene-change-se: [Cyber14-1](https://otologic.jp/free/se/cyber02.html)
    * decision-se: [Cyber15-1](https://otologic.jp/free/se/cyber02.html)
    * PET-frame-se: [Cyber16-2](https://otologic.jp/free/se/cyber02.html)
    * v-se: [Cyber17-1](https://otologic.jp/free/se/cyber02.html)

    </details>

6. [SAMMI](https://github.com/SAMMISolutions/SAMMI-Official/releases) のデック環境をインポートしてください。<br>※念のため、インポート前にバックアップを作成しておいてください。

    1. SAMMI を起動してください。
    2. リリースからダウンロードして解凍した中の SAMMI フォルダ内にあるデックの json ファイルを開き、中身をコピーしてください。
    3. その後、SAMMI 上で [Paste Deck] 項目を選択して、デックを展開してください。

    <br>

    > デック共有  
    > SAMMI で、共有したいデッキを選択して、その上で右クリックして「デッキをコピー」を選択します。これで、JSON のデッキデータがすべてクリップボードにコピーされる。その後、それをテキストファイルに貼り付けて、他の人と共有することができます。  
    > 　デッキをインポートするには、SAMMI のサイドメニューで Paste Deck を押してください。
    >
    > Share a deck  
    > In SAMMI, select a deck you wish to share with someone, right click on it and select Copy Deck. This will copy all your JSON deck data into your clipboard. You can then paste it into a text file to share with others.  
    > To Import a deck, press Paste Deck in SAMMI’s side menu.  
    > [SAMMI FAQ -Buttons & Commands-](https://sammi.solutions/docs/faq/commands)

## 環境

PC: [GL72M 7RDX](https://www.msi.com/Laptop/GL72M-7RDX/Specification)  
CPU: [i7-7700HQ CPU @ 2.80GHz 7th Gen](https://www.intel.co.jp/content/www/jp/ja/products/sku/97185/intel-core-i77700hq-processor-6m-cache-up-to-3-80-ghz/specifications.html)  
GPU: GeForce® GTX 1050 with 2GB GDDR5

## 注意

* Scene Collection Manager からエクスポートした json ファイルはOBS 標準の機能でもインポートすることができます。しかし、Scene Collection Manager からのエクスポート時に設定されたローカルファイルの一時的なパスを読み込んでしまうので**ローカルファイルとの紐付けが正しく行われません。**

    <details><summary>
    画像：シーンコレクションバックアップのインポート時の注意点
    </summary>
    
    ![kurocha-note-01](https://kurocha.jp/wp-content/uploads/2022/05/2022-05-09_17h11_06.jpg)
    
    ![kurocha-note-02](https://kurocha.jp/wp-content/uploads/2022/05/2022-05-09_17h17_02.jpg)
    
    > [OBSのバックアップを簡単便利にするプラグイン](https://kurocha.jp/obs-scene-collection-manager)

    </details>

* 本シーンコレクションは、[LioranBoard 2](https://github.com/LioranWaters/Lioranboard2Update) や [SAMMI](https://sammi.solutions/) を使用することを前提に作成しています。

* 本シーンコレクションを使用時に、OBS が重たい、またはフリーズするなどの症状が起きた場合は、下記リンクを参照に Windows のグラフィックス設定を見直したら改善されるかもしれません。

    > [『OBSトラブル対処方法』フリーズ＆固まる（応答無しや無反応）を解決【Vtuberラバルルによるゲーム実況のやり方講座】](https://youtu.be/KP3QfsjP66M)

* 本シーンコレクションは予告なく配布を終了する場合があります。

## 更新情報

* 2023/02/03:<br>[v1.0.0](https://github.com/DriCro6663/advanced-pet/releases/tag/v1.0.0) を公開。<br>ブートエフェクトの改善。エンドエフェクトの追加。

    <details><summary>
    これまでの更新情報
    </summary>

    * 2023/02/01:<br>[v0.0.5-beta](https://github.com/DriCro6663/advanced-pet/releases/tag/v0.0.5) を公開。<br>DS・4:3 シーンを追加。ED の追加。SAMMI のデックを整理：よく使う処理の関数化。

    * 2023/01/25:<br>[v0.0.4-beta](https://github.com/DriCro6663/advanced-pet/releases/tag/v0.0.4) を公開。<br>GBA-3:2 シーンを追加。コメントシーンの追加・整理。BGM, SE の追加。SAMMI のデックを追加。

    * 2023/01/21:<br>[v0.0.3-alpha](https://github.com/DriCro6663/advanced-pet/releases/tag/v0.0.3) を公開。<br>配信待機・ちょっと待って・配信終了シーンを追加。各アニメーション設定の整理。

    * 2023/01/18:<br>[v0.0.2-alpha](https://github.com/DriCro6663/advanced-pet/releases/tag/v0.0.2) を公開。タスクバーのアニメーション設定した。

    * 2023/01/13:<br>[v0.0.1-alpha](https://github.com/DriCro6663/advanced-pet/releases/tag/v0.0.1) を公開。とり、製作途中のバックアップ。

    </details>

## 開発者情報 & 文責

* [Github DriCro6663](https://github.com/DriCro6663)
* [Twitter Dri_Cro_6663](https://twitter.com/Dri_Cro_6663)
* [YouTube ドリクロ -DriCro-](https://www.youtube.com/channel/UCyWgav9wdiPVjYphB7jrWCQ)
* [PieceX DriCro6663](https://www.piecex.com/users/profile/DriCro6663)
* [ドリクロの備忘録](https://dri-cro-6663.jp/)
* dri.cro.6663@gmail.com

## クレジット

* BGM by [Oto.how](https://oto.how/)
* ED by [D-elf.com](https://www.d-elf.com/)
* SE by [OtoLogic](https://otologic.jp/) (CC BY 4.0)
* SE by [ジーソザイ](https://koukaon.g-sozai.com/)

## ライセンス

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/deed.ja"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Dataset" property="dct:title" rel="dct:type">OBS Scene Collection: Advanced-PET</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/DriCro6663/advanced-pet" property="cc:attributionName" rel="cc:attributionURL">Dri Cro</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

[LICENSE](.LICENSE) ファイルもご確認してください。
